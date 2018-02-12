
Debian
====================
This directory contains files used to package bitcoin-us/bitcoin-us
for Debian-based Linux systems. If you compile bitcoin-us/bitcoin-us-qt yourself, there are some useful files here.

## bitcoin-us: URI support ##


bitcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoin-us-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin-us128.png` to `/usr/share/pixmaps`

bitcoin-us-qt.protocol (KDE)

