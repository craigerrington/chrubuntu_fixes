chrubuntu_fixes
===============

Various fixes for Chrubuntu (specifically aimed at the ARM model Chromebook)

To fix the eratic behaviour of the trackpad in ChrUbuntu, simply clone this
repository and execute the script.

The script by default will set a "gb" keyboard map, simply uncomment the bottom
line for a US key map.

The script is *very* simple, and it does the following:

Backs up your X config to a folder called "backup" in your home directory

Moves into the X config directory

Downloads my X config files as a zip archive

Unzips the archive, and then deletes it

(then the optional keymap part)
