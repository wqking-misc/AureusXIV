
Debian
====================
This directory contains files used to package AXIVd/AXIV-qt
for Debian-based Linux systems. If you compile AXIVd/AXIV-qt yourself, there are some useful files here.

## AXIV: URI support ##


AXIV-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install AXIV-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your AXIVqt binary to `/usr/bin`
and the `../../share/pixmaps/AXIV128.png` to `/usr/share/pixmaps`

AXIV-qt.protocol (KDE)

