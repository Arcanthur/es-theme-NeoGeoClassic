=======NEO GEO CLASSIC THEME=======
=			  	  =
=           Version 1.0           =
=       Created by Arcanthur      =
=				  =
===================================

To use this theme you must install the emulationstation-dev branch.
This theme uses the grid view exclusively (for now).

---------------------------------
-  To install the dev branch    -
---------------------------------

Settings > Retropie setup > Manage Packages > Manage Experamental Packages

Scroll down and install Emulationstation-Dev from source.  Once the application has compiled you will need to reboot your system, and you should now be running the correct version.  You can verify by pressing start on your controller and checking the version # that displays at the bottom of the screen.

Next change the view type to Grid, then select Neo Geo Classic theme.

---------------------------------
- Systems currently supported   -
---------------------------------

3DO
Atari 2600
Atari 5200
Atari 7800
Atari Lynx
Atari Jaguar
Bandai Wonderswan
Bandai Wonderswan Color
Commodore Amiga
Commodore CD32
Commodore 64
Commodore Plus4
Commodore Vic/20
ColecoVision
Fairchild Channel F
FM Towns Marty
Mattel Intellivision
Microsoft MSX
Microsoft MSX2
Microsoft MS-DOS
Microsoft Xbox
Microsoft Xbox 360
NEC PC Engine
NEC PC Engine CD
NEC SuperGrafx
NEC Turbografx 16
NEC Turbografx CD
NEC PC-98
NEC PC-FX
Nintendo NES
Nintendo Famicom
Nintendo Famicom Disk System
Nintendo Gameboy
Nintendo Gameboy Color
Nintendo Gameboy Advance
Nintendo DS
Nintendo 3DS
Nintendo Gamecube
Nintendo SNES
Nintendo SNES MSU-1 (SNES CD)
Nintendo Super Famicom
Nintendo 64
Nintendo Wii
Nintendo Virtual Boy
ScummVM
Sega SG1000
Sega Master Sytem
Sega Mark III
Sega Genesis
Sega Megadrive
Sega 32X
Sega CD
Sega Saturn
Sega Dreamcast
Sega Gamegear
Sharp X68000
SNK Neo Geo
SNK Neo Geo Pocket
SNK Neo Geo Pocket Color
SNK Neo Geo CD
Sony PlayStation 1
Sony PlayStation 2
Sony PlayStation 3
Sony PlayStation Portable
Vectrex
ZX81
ZX Spectrum

-Custom collections
Favorites
Capcom arcade classics 
Konami arcade classics
SNK arcade classics
Gameboy Hacks
Gameboy Advance Hacks
Gamegear Hacks
Genesis Hacks
Super Nintendo Hacks

If assets don't load for your system check the folder name of your system and verify if matches the theme.

----------------------------------
-   To make additions / edits    -
----------------------------------

There are 3 locations you will need to add your content.

./art/logos/"system name".png
./art/console/"system name".png

and in the root of the theme you will also need a folder with your system name with the following files:

./System Name
	/theme.xml
	/tile.png
	/tile-selected.png

For example if you wanted to add Atari800 you will need the following:

./art/logos/atari800.png
./art/console/atari800.png
./atari800
	/theme.xml
	/tile.png
	/tile-selected.png
