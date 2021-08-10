#  ***bash-scripts***
- **Index**
	- [Autobinaries.sh](#Autobinaries.sh)
	- [Blighty](#Blighty)
		- [a](##dependencies)
	- [Bsr](#Bsr)	
	- [cheatsheet-i3](#cheatsheet-i3)
	- [dirwatch](#dirwatch)
	- [rofi_wifi_menu](#rofi_wifi_menu)
	- [status](#status)
	- [Toothy-bluetooth-Termial](#Toothy-bluetooth-Termial)
	- [wiiTurbo](#wiiTurbo)
	- [xranscreen](#xranscreen)


# Autobinaries.sh
Dependencies:
```bash
yay -S shc
```
Description:

Used for rutinary compiling and migration of several scripts at once (Those in the same folder as the script is)

--help :
```bash 
#DOCUMENTATION 
# Made by Gugeldot23
# The motivation of this script is to avoid repetitive compiling by shc of your scripts. 
# It automates it with all the files available in the directory executed 
# BE CAREFULL, BINARIES IN THE BINARY FORLDER WILL BE DELETED EVERY TIME THE SCRIPT IS 
# EXECUTED TO AVOID REPETITION
#
# DISCLAIMER: 
#	This script is concieved to be executed at this following location
#	The only compulsory thing is to have a directory called Binaries a level above where 
#   the script its executed
#   You can rename the folder if you want by replacing "Binaries" in variable binary_folder
# Represetnation of the script: 
# ├── Binaries --> Where they will be placed.
# │
# ├── Except--> Binaries you dont want to be deleted or Scripts you dont want to convert 
# │
# └── Script Folder --> No matter the name
#     ├── AutoBinaries.sh --> The script itself has to be placed at the directory 
#	  |					  of your scripts
#     └── YourScripts...
#
# MIGRATION OPTION ADDED: 
# Use --migrate argument to move Binaries files to /bin
# 
# SINGLE FILE MIGRATION OPTION ADDED: 
# Use --just argument and the name of the file to move Binaries files to /bin
# THANKS FOR USING IT!!
#
# MIGRATiON OPTION WITHOUT COMPILING: 
# Use --just-migrate argument to all move Binaries files to /bin
```
# Blighty
## dependencies
```bash
pacman -S xbacklight
```
Description:

A simple and somehow redundant simple interface of [xbacklight](https://wiki.archlinux.org/title/Backlight#xbacklight)
--help:

```bash'
__________.__  .__       .__     __          
\______   \  | |__| ____ |  |___/  |_ ___.__.
 |    |  _/  | |  |/ ___\|  |  \   __<   |  |
 |    |   \  |_|  / /_/  >   Y  \  |  \___  |
 |______  /____/__\___  /|___|  /__|  / ____|
        \/       /_____/      \/      \/     
------

Usage: 

blighty  [ ? (See value)] [-s | --set] VALUE ] | [ - VALUE ] | [ + VALUE ] 

------'
```

# Bsr
# cheatsheet-i3
# dirwatch
# rofi_wifi_menu
# status
# Toothy-bluetooth-Termial
# wiiTurbo
# xranscreen