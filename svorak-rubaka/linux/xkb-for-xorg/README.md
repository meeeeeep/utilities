Example usage
=============

Place layout file in
/usr/share/X11/xkb/symbols/svorak-r

Load it manually in X with "setxkbmap"
setxkbmap svorak-r

And don't forget to place the above command in ~/.xinitrc if you want the layout to load when your user runs "startx"

To enable globally for all users you probably can specify the layout in xorg.conf
