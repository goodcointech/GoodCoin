
Debian
====================
This directory contains files used to package goodcoind/goodcoin-qt
for Debian-based Linux systems. If you compile goodcoind/goodcoin-qt yourself, there are some useful files here.

## goodcoin: URI support ##


goodcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install goodcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your goodcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/goodcoin128.png` to `/usr/share/pixmaps`

goodcoin-qt.protocol (KDE)

