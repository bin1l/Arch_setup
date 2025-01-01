# Arch_setup TBW
Steps to setup a new installation of arch like TBW "**The Binil's Way**"


# Install Arch
duh...obviously installing the arch is the fist step. Take care to
* use `nvidia proprietary drivers` (best performance drivers for nvidia card)
* use `grub` 
* and `kde plasma` for high customizability and efficiency)
* enable `zram compression` to reduce overhead on I/O (specially good for usb boot)

# Theming
Change the `fekking wallpaper` first of all dude....!!(find good ones in [Wallpapers](https://github.com/bin1l/Arch_setup/tree/main/Pictures/Wallpapers)

yeah....now peace..find and use the given styles
* Colors:`Breeze Dark`
* App Style:`Breeze`
* Plasma Style:`Breeze`
* Window Decoration:`Breeze`
* Icons:`Tela Circle dark`
* Cursors:`Tela Circle`

# Packages
Install the packages using the file [pkglist.txt](https://github.com/bin1l/Arch_setup/blob/main/pkglist.txt)
``` bash
sudo pacman -S --needed - < pkglist.txt
```
additionally to create the pkglist.txt file use the following command
```bash
sudo pacman -Qq > pkglist.txt
```
# Terminal 
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
## Set up starship
add the following to shell config
```bash
#if shell is bash use this
eval "$(starship init bash)"
```
```zsh
#if shell is zsh use this
eval "$(starship init zsh)"
```
set up starship config
``` bash
#create starship config file
mkdir -p ~/.config && touch ~/.config/starship.toml
```
download the Gruvbox Rainbow Preset [toml-file](gruvbox-rainbow.toml) and move the file 
```bash
mv starship.toml ~/.config/starship.toml
```

## Setup Mozilla
* use the Autumn Twining by if_tea
* disable firefox studies and personalized ads
* install ublock origin and bitwarden







