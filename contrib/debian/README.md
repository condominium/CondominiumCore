
Debian
====================
This directory contains files used to package condominiumd/condominium-qt
for Debian-based Linux systems. If you compile condominiumd/condominium-qt yourself, there are some useful files here.

## condominium: URI support ##


condominium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install condominium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your condominiumqt binary to `/usr/bin`
and the `../../share/pixmaps/condominium128.png` to `/usr/share/pixmaps`

condominium-qt.protocol (KDE)

