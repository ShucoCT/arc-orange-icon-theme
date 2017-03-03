# Arc Orange Icon Theme

This is a fork of the Arc Icon theme at https://github.com/horst3180/arc-icon-theme, but with colored icons with orange to fit with Ubuntu 16.04 Xenial and Unity original icons.

### Requirements

This Icons set is modified to inherit [Paper icon](https://github.com/snwh/paper-gtk-theme) set for missing icons instead of Moka. If Paper icon is not installed it will use the Gnome icon theme as fallback.

To change the application icons, edit `Arc/index.theme` and replace `Paper` with the name of your preferred icon theme

For example, if you like the Faenza icon theme, change

    [Icon Theme]
    Name=Arc
    Inherits=Paper,Adwaita,gnome,hicolor
    Comment=Arc Icon theme

to

    [Icon Theme]
    Name=Arc
    Inherits=Faenza,Adwaita,gnome,hicolor
    Comment=Arc Icon theme

### Installation

Run the following to install the icon set:

    git clone https://github.com/chaouimar1/arc-orange-icon-theme.git
    cd arc-orange-icon-theme
    sudo cp -R ./Arc-Icons-Orange/ /usr/share/icons/

### Uninstall

Run

    sudo rm -rf /usr/share/icons/Arc-Icons-Orange

### Preview
![Preview](https://i.imgur.com/Iyxz3IO.png)

License: GPLv3
