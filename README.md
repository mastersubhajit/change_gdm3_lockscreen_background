# change-gdm3-background
For now this project only supports Ubuntu/Pop-Os-20.04 and 20.10 version!

### Features
* Change login wallpaper
* Change login Background from wallpaper located in __/usr/share/Wallpapers__
* Change login screen shield. (Login screen's lockscreen image)
* Enable / disable user for login as changes takes place for only one user. 
* Proven to work gnome-shell 3.36 onwards as it has support for it.__Might also work earlier versions but is not tested and in case if it is not working nothing can be done to fix.__

# gdm3 Lock Screen Background Changer
Gnome GDM Login Background Changer. Easy and Fast Login Wallpaper Manipulation.

## Warning
This script won't work with any previous versions of Ubuntu/Pop-Os because they comes with older version of gdm rather than gdm3.36. It also won't work if your system is set to a custom gdm3 theme. You will have to reset to the default configuration of gdm3 before using the script. This script is for default Ubuntu theme (Yaru). This tool was made specifically to work with Ubuntu or Pop OS 20.04 and 20.10 as it now bundles all configuration files inside a .gresource file.

### Tested On
* Ubuntu 20.04/20.10
* Pop Os 20.04/20.10

# Installation Steps
* Step 1: Install libglib2.0-dev-bin using `sudo apt-get installlibglib2.0-dev-bin`
* Step 2: clone the repo using `WGET` or `git clone`:
https://github.com/mastersubhajit/change-gdm3-background.git
* Step 3: make it executable using `sudo chmod +x change-gdm3-background`

## Usage
Run the script with root privileges such as `sudo ./change-gdm-background /path/to/image`
* If you see a message login image sucessfully changed, then, when you restart gdm or reboot your computer, your gdm background should be covered with the image you selected.
You can always restore your original gdm theme any time with `sudo ./change-gdm-background --restore`

* This also supports solid colour background set, to use it simply type `sudo ./change-gdm-background \#yourhexcode` in place of "`#yourhexcode`" insert code of six characters like "#923641" or of three characters like "#8ca" without quotes.

## Known limitations and issues
Feel free to report issues until now there is no known issues.
# THANK YOU
