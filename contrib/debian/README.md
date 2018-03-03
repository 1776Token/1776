
Debian
====================
This directory contains files used to package 1776d/1776-qt
for Debian-based Linux systems. If you compile 1776d/1776-qt yourself, there are some useful files here.

## 1776: URI support ##


1776-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install 1776-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your 1776qt binary to `/usr/bin`
and the `../../share/pixmaps/1776128.png` to `/usr/share/pixmaps`

1776-qt.protocol (KDE)

