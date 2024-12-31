# Arch_setup
Steps to setup a new installation of arch like "my way"


# Install Arch
duh...obviously installing the arch is the fist step. Take care to
* use `nvidia proprietary drivers` (best performance drivers for nvidia card)
* use `grub` 
* and `kde plasma` for high customizability and efficiency)
* enable `zram compression` to reduce overhead on I/O (specially good for usb boot)

# Packages
Install the packages using the file `pkglist.txt`
``` bash
sudo pacman -S --needed - < pkglist.txt
```
