
Debian
====================
This directory contains files used to package chunicoind/chunicoin-qt
for Debian-based Linux systems. If you compile chunicoind/chunicoin-qt yourself, there are some useful files here.

## chunicoin: URI support ##


chunicoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install chunicoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your chunicoinqt binary to `/usr/bin`
and the `../../share/pixmaps/chunicoin128.png` to `/usr/share/pixmaps`

chunicoin-qt.protocol (KDE)

