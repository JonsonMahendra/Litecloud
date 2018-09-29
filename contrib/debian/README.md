
Debian
====================
This directory contains files used to package litecloudd/litecloud-qt
for Debian-based Linux systems. If you compile litecloudd/litecloud-qt yourself, there are some useful files here.

## litecloud: URI support ##


litecloud-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install litecloud-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your litecloudqt binary to `/usr/bin`
and the `../../share/pixmaps/litecloud128.png` to `/usr/share/pixmaps`

litecloud-qt.protocol (KDE)

