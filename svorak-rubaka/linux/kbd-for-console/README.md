Example usage
=============

Put somewhere in
/usr/share/kbd/keymaps

For example
/usr/share/kbd/keymaps/custom/svorak-r.map.gz

To load at boot select keymap in /etc/rc.conf (arch linux)
KEYMAP="svorak-r"

Or load it manually with "loadkeys"
loadkeys /usr/share/kbd/keymaps/custom/svorak-r.map.gz
