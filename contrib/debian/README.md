
Debian
====================
This directory contains files used to package cryptoplayd/cryptoplay-qt
for Debian-based Linux systems. If you compile cryptoplayd/cryptoplay-qt yourself, there are some useful files here.

## cryptoplay: URI support ##


cryptoplay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cryptoplay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cryptoplay-qt binary to `/usr/bin`
and the `../../share/pixmaps/cryptoplay128.png` to `/usr/share/pixmaps`

cryptoplay-qt.protocol (KDE)

