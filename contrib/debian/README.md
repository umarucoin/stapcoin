
Debian
====================
This directory contains files used to package stapd/stap-qt
for Debian-based Linux systems. If you compile stapd/stap-qt yourself, there are some useful files here.

## stap: URI support ##


stap-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stap-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stap-qt binary to `/usr/bin`
and the `../../share/pixmaps/stap128.png` to `/usr/share/pixmaps`

stap-qt.protocol (KDE)

