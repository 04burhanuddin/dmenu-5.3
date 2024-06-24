# Burhan Build of Dynamic Menu
> Verison 5.3

dmenu is an efficient dynamic menu for X. from [suckless.org](https://tools.suckless.org/dmenu/)


## Requirements
In order to build dmenu you need the Xlib header files.


## Installation
- Edit config.mk to match your local setup (dmenu is installed into the /usr/local namespace by default).
- Afterwards enter the following command to build and install dmenu
(if necessary as root):

```
git clone https://github.com/04burhanuddin/dmenu.git
cd dmenu
make clean install

# as root
sudo make clean install
```

## Patch & Features

- [Center](https://tools.suckless.org/dmenu/patches/center/) - This patch centers dmenu in the middle of the screen.
- [Line-Height](https://tools.suckless.org/dmenu/patches/line-height/) - The patch adds a '-h' option, which sets the minimum height of a dmenu line

## Running dmenu
See the man page for details.
