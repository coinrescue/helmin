
Debian
====================
This directory contains files used to package helmind/helmin-qt
for Debian-based Linux systems. If you compile helmind/helmin-qt yourself, there are some useful files here.

## helmin: URI support ##


helmin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install helmin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your helminqt binary to `/usr/bin`
and the `../../share/pixmaps/helmin128.png` to `/usr/share/pixmaps`

helmin-qt.protocol (KDE)

