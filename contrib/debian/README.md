
Debian
====================
This directory contains files used to package bocod/boco-qt
for Debian-based Linux systems. If you compile bocod/boco-qt yourself, there are some useful files here.

## pivx: URI support ##


boco-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install boco-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your boco-qt binary to `/usr/bin`
and the `../../share/pixmaps/boco128.png` to `/usr/share/pixmaps`

boco-qt.protocol (KDE)

