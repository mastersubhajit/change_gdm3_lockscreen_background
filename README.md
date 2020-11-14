# change-gdm3-background
For now this project only supports Ubuntu/Pop-Os-20.04 and 20.10 version!
__New__ support for Arch linux Gnome environment.

### Features
* Change login wallpaper
* Change login Background from wallpaper located in __/usr/share/Wallpapers__
* Change login screen shield. (Login screen's lockscreen image)
* Enable / disable user for login as changes takes place for only one user. 
* Proven to work gnome-shell 3.36 onwards as it has support for it. __Might also work earlier versions but is not tested and in case if it is not working nothing can be done to fix.__

# gdm3 Lock Screen Background Changer
Gnome GDM Login Background Changer. Easy and Fast Login Wallpaper Manipulation.

## Warning
This script won't work with any previous versions of Ubuntu/Pop-Os because they comes with older version of gdm rather than gdm3.36. It also won't work if your system is set to a custom gdm3 theme. You will have to reset to the default configuration of gdm3 before using the script. This script is for default Ubuntu theme (Yaru). This tool was made specifically to work with Ubuntu or Pop OS 20.04 and 20.10 as it now bundles all configuration files inside a .gresource file.

### Tested On 
* Ubuntu 20.04/20.10
* Pop Os 20.04/20.10
* __New__ Support for Arch Linux

# Installation Steps (Ubuntu) 
* Step 1: Install libglib2.0-dev-bin using `sudo apt-get install libglib2.0-dev-bin`
* Step 2: clone the repo using `WGET` or `git clone`:
`wget https://github.com/mastersubhajit/change-gdm3-background/raw/main/change-gdm3-background.sh`
* Step 3: make it executable using `sudo chmod +x change-gdm3-background.sh`

## Usage (Ubuntu)
Run the script with root privileges such as `sudo ./change-gdm3-background.sh /path/to/image`
* If you see a message login image sucessfully changed, then, when you restart gdm or reboot your computer, your gdm background should be covered with the image you selected.
You can always restore your original gdm theme any time with `sudo ./change-gdm3-background.sh --restore`

* This also supports solid colour background set, to use it simply type `sudo ./change-gdm3-background.sh \#yourhexcode` in place of "`#yourhexcode`" insert code of six characters like "#923641" or of three characters like "#8ca" without quotes.

# Installation Steps (Arch)
* Step 1: Install glib2 for Arch using `Sudo pacman -S 
glib2`
* Step 2: `wget https://github.com/mastersubhajit/change-gdm3-background/raw/main/arch-change-gdm3-background`
* Step 3: `chmod +x arch-change-gdm-background`

## Usage (Arch)
* Run the script with root privileges such as `sudo ./arch-change-gdm-background /path/to/image`.
* If you see a message login image sucessfully changed, then, when you `restart` gdm or `reboot` your computer, your gdm background should be covered with the image you selected.
* You can restore your original gdm theme any time with `sudo ./arch-change-gdm-background --restore`.
* This also supports solid colour background set, to use it simply type `sudo ./arch-change-gdm-background \#yourhexcode` in place of __"#yourhexcode"__ insert code of six characters like "#923641" or of three characters like "#8ca" without quotes.

__For more information about changing GDM background or if you with to do it manually see GDM article on ArchWiki__ .
## Known limitations and issues
Feel free to report issues until now there is no known issues.
# Coming Soon
__Support for Fedora 32 or higher.__
