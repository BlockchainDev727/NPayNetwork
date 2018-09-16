
Debian
====================
This directory contains files used to package npaynetworkd/npaynetwork-qt
for Debian-based Linux systems. If you compile npaynetworkd/npaynetwork-qt yourself, there are some useful files here.

## npaynetwork: URI support ##


npaynetwork-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install npaynetwork-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your npaynetworkqt binary to `/usr/bin`
and the `../../share/pixmaps/npaynetwork128.png` to `/usr/share/pixmaps`

npaynetwork-qt.protocol (KDE)

