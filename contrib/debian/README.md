
Debian
====================
This directory contains files used to package zondd/zond-qt
for Debian-based Linux systems. If you compile zondd/zond-qt yourself, there are some useful files here.

## zond: URI support ##


zond-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zond-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zondqt binary to `/usr/bin`
and the `../../share/pixmaps/zond128.png` to `/usr/share/pixmaps`

zond-qt.protocol (KDE)

