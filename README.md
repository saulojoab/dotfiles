# dotfiles
My Arch Linux dotfiles 

### Waybar
https://github.com/UnFunnyGuy/hyprland-dots/tree/master/waybar

### Display Manager

SDDM with https://github.com/Keyitdev/sddm-astronaut-theme/tree/master/Themes

### APP LANCHER: Walker

https://github.com/abenz1267/walker 
- easy install with 
```bash 
yay -S walker-bin elephant elephant-providerlist elephant-desktopapplications
elephant service enable
```

### FILE MANAGER: Nautilus
https://archlinux.org/packages/extra/x86_64/nautilus/
- THEME: Orchis-Dark
```bash
# Install the theme
sudo pacman -S orchis-theme

# Open theme folder with vscode
code /usr/share/themes

# Replace all instances of #2C2C2C on Orchis-Dark with rgba(22, 22, 22, 0.8)
# This will make the background transparent. TODO: figure out how to make other parts transparent.
```

### WALLPAPER: Hyprpaper
