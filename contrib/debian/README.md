
Debian
====================
This directory contains files used to package greencoind/greencoin-qt
for Debian-based Linux systems. If you compile greencoind/greencoin-qt yourself, there are some useful files here.

## greencoin: URI support ##


greencoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install greencoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your greencoinqt binary to `/usr/bin`
and the `../../share/pixmaps/greencoin128.png` to `/usr/share/pixmaps`

greencoin-qt.protocol (KDE)

