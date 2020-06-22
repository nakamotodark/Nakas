
Debian
====================
This directory contains files used to package nakasd/nakas-qt
for Debian-based Linux systems. If you compile nakasd/nakas-qt yourself, there are some useful files here.

## nakas: URI support ##


nakas-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nakas-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nakasqt binary to `/usr/bin`
and the `../../share/pixmaps/nakas128.png` to `/usr/share/pixmaps`

nakas-qt.protocol (KDE)

