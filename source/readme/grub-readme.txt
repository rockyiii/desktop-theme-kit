- Grub 2 Themes -

To enable Grub2 themes, add the following line to /etc/default/grub

GRUB_GFXMODE=800x600
GRUB_THEME=/usr/share/desktop-theme-kit/grub/theme/theme.txt

and run as root

update-grub

You are free to use higher GFXMODE settings, 800x600 just should be a safe bet.

