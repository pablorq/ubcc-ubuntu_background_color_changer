# UBCC - Ubuntu Background Color Changer
Ubuntu 19.10 has no option to configure the background color from boot screen to login. UBCC solves that!

## Install
No need to install packages. Just use it!
- Download and extract the files
- Change file permissions

`chmod u+x ubcc`

- Double clic over ubcc file

## Usage
You can choose from 3 different inputs:
- Color pickes
- Themes: more than 30 options!
- Manual entry

After select a background color, you must confirm this color to be applied. To apply the selected background you must enter a root or sudo password.

You can see a log of the actions done, and also a log file is created next to ubcc file.

## How it works
To change the background color is necessary to change 3 different files with 3 different color codes and also update grub to applythe changes to boot screen.
The background color is configured for grub boot screen, plymouth screen with Ubuntu logo and Gnome shell login screen.
The app also makes a backup of your files before to be modified.
