# Taiga-Grub-Theme
Basically just "Distro Grub Themes" arch theme with a modified background.

Original: [Link](https://www.pling.com/p/1482847/)

# Installation
1. Just copy the "arch-linux" folder into /boot/grub/themes/ (create the folder if it doesn't exist)
2. Edit /etc/default/grub with your editor of choice and add ```GRUB_THEME=/boot/grub/themes/arch-linux/theme.txt"``` at the end
3. Run ```grub-mkconifg -o /boot/grub/grub.cfg```
4. Profit
