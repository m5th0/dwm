### IMPORTANT

[dwm](https://dwm.suckless.org/) is a dynamic window manager by suckless.org

* this is my build of dwm, for backup purposes however you may install it for ease of life

### Installation

clone this repository by 
```bash
git clone https://github.com/m5th0/dwm.git
```
then finally compile this with
```bash
sudo make clean install
```
**STARTX:** If you want to run dwm by startx, add the following to your .xinitrc:
	exec dwm

### Configuration

configuration is done by editing the config.h file and then re-compiling

**Status Bar:** this build of dwm uses dwmblocks for statusbar however you can change it by editing-
```#define STATUSBAR "dwmblocks"```
in the config.h file 

