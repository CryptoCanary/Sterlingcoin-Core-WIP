
Debian
====================
This directory contains files used to package sterlingcoind/sterlingcoin-qt
for Debian-based Linux systems. If you compile sterlingcoind/sterlingcoin-qt yourself, there are some useful files here.

## sterlingcoin: URI support ##


sterlingcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sterlingcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sterlingcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/sterlingcoin128.png` to `/usr/share/pixmaps`

sterlingcoin-qt.protocol (KDE)

