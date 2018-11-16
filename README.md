# Desaturin

a GTK2,and GTK3 file for the Gnome-desktop

![s](https://cn.opendesktop.org/img/c/8/b/9/6281cb2203a84b65b8a285877202095297c7.jpg)



A completely colorless (desaturated) version of my Telinkrin-theme.

https://github.com/paullinuxthemer/Telinkrin-GTK

Please, try and rate, comment. Any input or criticism is welcome.

There is an matching iconset avaliable : Suru-grey by Willscreel

https://www.opendesktop.org/p/1233057/


## Issues:

You will notice that resizing the sidebar in nautilus behaves strange. This is not a bug. Visually the sidebar will not change (to keep it alligned with the headerbar), but you will still see the pointer for resizing. For this to work properly, pleas keep the sidebar-size small as possible.


## Requirements:

GTK+ 3.20 or later. Only standard (or Ubuntu) gnome-desktop is supported. Ready for Ubuntu 18.04
Disable gnome-extensions that reside on the headerbar because they mess up the headerbar-theming.

Window-buttons-layout (min/max/close) at the right side. (DO NOT PUT IT ON THE LEFT-SIDE)
No support for left-sided buttons for the moment...

GTK2 ENGINES REQUIREMENT

- GTK2 engine Murrine
- GTK2 engine Pixbuf

Fedora/RedHat distros:
yum install gtk-murrine-engine gtk2-engines

Ubuntu/Mint/Debian distros:
sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf

ArchLinux:
pacman -S gtk-engine-murrine gtk-engines

## What to do:

Extract and put it into the themes directory i.e. ~/.themes/ or /usr/share/themes/ (create it if necessary).Then change the theme via distribution specific tool like Gnome tweak tool or Unity tweak tool, etc. (If you use Snap-packages instead of app's from the normal repositories than definitely put the theme to /usr/share/themes/.
