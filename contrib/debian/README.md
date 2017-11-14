
Debian
====================
This directory contains files used to package ltucoind/ltucoin-qt
for Debian-based Linux systems. If you compile ltucoind/ltucoin-qt yourself, there are some useful files here.

## ltucoin: URI support ##


ltucoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ltucoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ltucoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/ltucoin128.png` to `/usr/share/pixmaps`

ltucoin-qt.protocol (KDE)

