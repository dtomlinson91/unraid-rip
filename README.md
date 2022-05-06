# rip

This is the repository for the unraid rip plugin.

<img src="https://git.panaetius.co.uk/dtomlinson91/unraid-rip/raw/branch/master/assets/unraid-rip.png"/>

rip is a command-line deletion tool focused on safety, ergonomics, and performance. It favors a simple interface, and does not implement the xdg-trash spec or attempt to achieve the same goals.

Deleted files get sent to the graveyard (`/tmp/graveyard-$USER` by default, see notes on changing this) under their absolute path, giving you a chance to recover them. No data is overwritten. If files that share the same path are deleted, they will be renamed as numbered backups.

For more information see the [rip repository](https://github.com/nivekuil/rip).
## dev

Drone builds the plugin source using cargo on a new tag creation.

Tag versions follow rip releases.
