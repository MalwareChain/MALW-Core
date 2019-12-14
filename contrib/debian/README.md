
Debian
====================
This directory contains files used to package malwarechaind/malwarechain-qt
for Debian-based Linux systems. If you compile malwarechaind/malwarechain-qt yourself, there are some useful files here.

## malwarechain: URI support ##


malwarechain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install malwarechain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your malwarechainqt binary to `/usr/bin`
and the `../../share/pixmaps/malwarechain128.png` to `/usr/share/pixmaps`

malwarechain-qt.protocol (KDE)

