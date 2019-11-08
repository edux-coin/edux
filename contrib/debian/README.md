
Debian
====================
This directory contains files used to package eduxd/edux-qt
for Debian-based Linux systems. If you compile eduxd/edux-qt yourself, there are some useful files here.

## edux: URI support ##


edux-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install edux-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eduxqt binary to `/usr/bin`
and the `../../share/pixmaps/edux128.png` to `/usr/share/pixmaps`

edux-qt.protocol (KDE)

