
Debian
====================
This directory contains files used to package sedusd/sedus-qt
for Debian-based Linux systems. If you compile sedusd/sedus-qt yourself, there are some useful files here.

## sedus: URI support ##


sedus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sedus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sedus-qt binary to `/usr/bin`
and the `../../share/pixmaps/sedus128.png` to `/usr/share/pixmaps`

sedus-qt.protocol (KDE)

