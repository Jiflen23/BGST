
Debian
====================
This directory contains files used to package stotinkad/stotinka-qt
for Debian-based Linux systems. If you compile stotinkad/stotinka-qt yourself, there are some useful files here.

## stotinka: URI support ##


stotinka-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stotinka-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stotinkaqt binary to `/usr/bin`
and the `../../share/pixmaps/stotinka128.png` to `/usr/share/pixmaps`

stotinka-qt.protocol (KDE)

