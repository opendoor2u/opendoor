
Debian
====================
This directory contains files used to package opendoord/opendoor-qt
for Debian-based Linux systems. If you compile opendoord/opendoor-qt yourself, there are some useful files here.

## opendoor: URI support ##


opendoor-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install opendoor-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your opendoor-qt binary to `/usr/bin`
and the `../../share/pixmaps/opendoor128.png` to `/usr/share/pixmaps`

opendoor-qt.protocol (KDE)

