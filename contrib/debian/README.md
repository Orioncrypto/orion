
Debian
====================
This directory contains files used to package oriond/orion-qt
for Debian-based Linux systems. If you compile oriond/orion-qt yourself, there are some useful files here.

## orion: URI support ##


orion-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install orion-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your orionqt binary to `/usr/bin`
and the `../../share/pixmaps/orion128.png` to `/usr/share/pixmaps`

orion-qt.protocol (KDE)

