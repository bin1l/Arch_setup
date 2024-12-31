# Arch_setup TBW
Steps to setup a new installation of arch like TBW "**The Binil's Way**"


# Install Arch
duh...obviously installing the arch is the fist step. Take care to
* use `nvidia proprietary drivers` (best performance drivers for nvidia card)
* use `grub` 
* and `kde plasma` for high customizability and efficiency)
* enable `zram compression` to reduce overhead on I/O (specially good for usb boot)

# Theming
Change the `fekking wallpaper` first of all dude....!!(find good ones in Wall)

yeah....now peace..find and use the given styles
* Colors:`Breeze Dark`
* App Style:`Breeze`
* Plasma Style:`Breeze`
* Window Decoration:`Breeze`
* Icons:`Tela Circle dark`
* Cursors:`Tela Circle`

# Packages
Install the packages using the file `pkglist.txt`
``` bash
sudo pacman -S --needed - < pkglist.txt
```
## Set up ghostty
Edit the ghostty config file
```bash
#open the config file

nano ~/.config/ghostty/config
```

add the following instructions
```bash

theme=Nocturnal Winter
title = " "
mouse-hide-while-typing
```
## Setup Mozilla
* use the Autumn Twining by if_tea
* disable firefox studies and personalized ads
* install ublock origin and bitwarden







