
Debian
====================
This directory contains files used to package peepcoind/peepcoin-qt
for Debian-based Linux systems. If you compile peepcoind/peepcoin-qt yourself, there are some useful files here.

## peepcoin: URI support ##


peepcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install peepcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your peepcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/peepcoin128.png` to `/usr/share/pixmaps`

peepcoin-qt.protocol (KDE)

