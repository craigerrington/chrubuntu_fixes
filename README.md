chrubuntu_fixes
===============

Various fixes for Chrubuntu (specifically aimed at the ARM model Chromebook)

To fix the eratic behaviour of the trackpad in ChrUbuntu, simply clone this
repository and execute the script.

The script by default will set a "gb" keyboard map, simply uncomment the bottom
line for a US key map.

The script is *very* simple, and iy does the following:

backs up your X config to a folder called "backup" in your home directory

moves into the X config directory

downloads my X config files as a zip archive

unzips the archive, and then deletes it

(then the optional keymap part)
