
Debian
====================
This directory contains files used to package rogaversed/rogaverse-qt
for Debian-based Linux systems. If you compile rogaversed/rogaverse-qt yourself, there are some useful files here.

## rogaverse: URI support ##


rogaverse-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rogaverse-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rogaverseqt binary to `/usr/bin`
and the `../../share/pixmaps/rogaverse128.png` to `/usr/share/pixmaps`

rogaverse-qt.protocol (KDE)

