
Debian
====================
This directory contains files used to package stakecubed/stakecube-qt
for Debian-based Linux systems. If you compile stakecubed/stakecube-qt yourself, there are some useful files here.

## stakecube: URI support ##


stakecube-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stakecube-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stakecube-qt binary to `/usr/bin`
and the `../../share/pixmaps/stakecube128.png` to `/usr/share/pixmaps`

stakecube-qt.protocol (KDE)

