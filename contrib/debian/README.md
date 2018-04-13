
Debian
====================
This directory contains files used to package Flashpaychaind/Flashpaychain-qt
for Debian-based Linux systems. If you compile Flashpaychaind/Flashpaychain-qt yourself, there are some useful files here.

## Flashpaychain: URI support ##


Flashpaychain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Flashpaychain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Flashpaychain-qt binary to `/usr/bin`
and the `../../share/pixmaps/Flashpaychain128.png` to `/usr/share/pixmaps`

Flashpaychain-qt.protocol (KDE)

