
Debian
====================
This directory contains files used to package streamitcoind/streamitcoin-qt
for Debian-based Linux systems. If you compile streamitcoind/streamitcoin-qt yourself, there are some useful files here.

## streamitcoin: URI support ##


streamitcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install streamitcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your streamitcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/streamitcoin128.png` to `/usr/share/pixmaps`

streamitcoin-qt.protocol (KDE)

