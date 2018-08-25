
Debian
====================
This directory contains files used to package armageddond/armageddon-qt
for Debian-based Linux systems. If you compile armageddond/armageddon-qt yourself, there are some useful files here.

## armageddon: URI support ##


armageddon-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install armageddon-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your armageddonqt binary to `/usr/bin`
and the `../../share/pixmaps/armageddon128.png` to `/usr/share/pixmaps`

armageddon-qt.protocol (KDE)

