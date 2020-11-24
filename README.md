# rEFInd-minimal-drunkcj
rEFInd is an easy to use boot manager for UEFI based systems. This is a clean and minimal theme for it.

![Screenshot](https://i.imgur.com/TCKkbpp.jpg)

This theme is inspired from ![rEFInd-minimal](https://github.com/EvanPurkhiser/rEFInd-minimal) by ![EvanPurkhiser](https://github.com/EvanPurkhiser)
## Usage
1. Locate your refind EFI directory. This is commonly ```/boot/EFI/refind``` though it will depend on where you mount your ESP and where rEFInd is installed.  ```fdisk -l``` and ```mount``` may help.

2. Create a folder called themes inside it, if it doesn't already exist 
3. Clone this repository into the themes directory using
4. To enable the theme add  ```include themes/rEFInd-minimal-drunkcj/theme.conf``` at the end of ```refind.conf```.
### Representation
* Up arrow indicates reboot
* Down arrow indicates shutdown
* Black chip indicates bios
