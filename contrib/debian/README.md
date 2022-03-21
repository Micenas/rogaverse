
Debian
====================
This directory contains files used to package birjeesd/birjees-qt
for Debian-based Linux systems. If you compile birjeesd/birjees-qt yourself, there are some useful files here.

## birjees: URI support ##


birjees-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install birjees-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your birjeesqt binary to `/usr/bin`
and the `../../share/pixmaps/birjees128.png` to `/usr/share/pixmaps`

birjees-qt.protocol (KDE)

