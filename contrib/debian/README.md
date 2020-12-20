
Debian
====================
This directory contains files used to package securecloud2d/securecloud2-qt
for Debian-based Linux systems. If you compile securecloud2d/securecloud2-qt yourself, there are some useful files here.

## securecloud2: URI support ##


securecloud2-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install securecloud2-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your securecloud2-qt binary to `/usr/bin`
and the `../../share/pixmaps/securecloud2128.png` to `/usr/share/pixmaps`

securecloud2-qt.protocol (KDE)

