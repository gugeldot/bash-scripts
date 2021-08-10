#  ***bash-scripts***
- **Index**
	- [Autobinaries.sh](#Autobinaries)
	- [Blighty](#Blighty)
	- [dirwatch](#dirwatch)
	- [status](#status)
	- [wiiTurbo](#wiiTurbo)
	- [xranscreen](#xranscreen)


# Autobinaries
**Dependencies:**
```bash
yay -S shc
```
**Description:**

Used for rutinary compiling and migration of several scripts at once (Those in the same folder as the script is)

**--help:**
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
**Dependencies:**
```bash
pacman -S xbacklight
```
**Description:**

A simple and somehow redundant simple interface of [xbacklight](https://wiki.archlinux.org/title/Backlight#xbacklight)

**--help:**

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

# dirwatch
**Dependencies:**
```bash
pacman -S figlet
```
**Description:** 

Lists and updates frequently a directory

# status
**Dependencies:**
```bash
pacman -S acpi
```
**Description:**

Returns in a single string freespace in /dev/sda3 and battery left. Uncommented some code that show it in a more detailed way

# wiiTurbo
**Dependencies:**
```bash
pacman -S nmcli
```
*Also uses Network Manager*

**Description**

An easy way of controling nmcli when you don't know other people have made nmcli interfaces like [nmcli-rofi](https://github.com/sineto/nmcli-rofi)

**--help**
```bash'
 __      __ ______________           ___           
/  \    /  \__|__\__   ___/_ ________\_ |__   ____  
\   \/\/   /  |  | |   | |  |  \_  __ \ __ \ /  _ \ 
 \        /|  |  | |   | |  |  /|  | \/ \_\ (  <_> )
  \__/\  / |__|__| |___| |____/ |__|  |___  /\____/ 
       \/                                  \/        
-----------------------------------------------------

Usage: 

wiiTurbo [ -scan | -status | -on | -off | -restart ] [-connect | -disconnect SSID [PASSWD]]
```
# xranscreen
**Dependencies:**
```bash
pacman -S xrandr
```
**Description:**

A script to automate use of xrandr with some preset settings

**--help:**
```bash'
____  ___                      _________                                   
\   \/  /___________    ____  /   _____/ ___________   ____   ____   ____  
 \     /\_  __ \__  \  /    \ \_____  \_/ ___\_  __ \_/ __ \_/ __ \ /    \ 
 /     \ |  | \// __ \|   |  \/        \  \___|  | \/\  ___/\  ___/|   |  \
/___/\  \|__|  (____  /___|  /_______  /\___  >__|    \___  >\___  >___|  /
      \_/           \/     \/        \/     \/            \/     \/     \/ 


Usage: xranscreen [ off  | add  | duplicate ]

Manipulate the script for manipulate settings 

Thanks for using it!
```