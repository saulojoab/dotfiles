# <center><samp>dotfiles ⚙️</samp></center>

<img width="1920" height="1081" alt="image" src="https://github.com/user-attachments/assets/2a30d3d0-19c6-45c8-b6e4-2a60716bd33a" />

<samp>A curated set of Arch Linux dotfiles and configuration for Hyprland, Waybar, Kitty, Nautilus and other desktop components.</samp>

## <samp>Table of contents</samp>

- <samp>Waybar 🧭</samp>
- <samp>App launcher — Walker 🚀</samp>
- <samp>File manager — Nautilus 📁</samp>
- <samp>Wallpaper — Hyprpaper 🖼️</samp>
- <samp>External libraries 📦</samp>

## <samp>Waybar 🧭</samp>

<samp>Configuration for Waybar is a modified version of:</samp>

https://github.com/UnFunnyGuy/hyprland-dots/tree/master/waybar

## <samp>App launcher — Walker 🚀</samp>

<samp>Walker is the launcher I use. Install it from the AUR:</samp>

```bash
yay -S walker-bin elephant elephant-providerlist elephant-desktopapplications
```

<samp>Enable the Elephant service:</samp>

```bash
elephant service enable
```

## <samp>File manager — Nautilus 📁</samp>

<samp>Nautilus is the default file manager in this setup.</samp>

<samp>Package:</samp>
https://archlinux.org/packages/extra/x86_64/nautilus/

<samp>Theme: Orchis-Dark</samp>

<samp>Install the theme and open the theme folder:</samp>

```bash
sudo pacman -S orchis-theme
code /usr/share/themes
```

<samp>Tip: to make the Orchis-Dark background slightly transparent you can replace occurrences of `#2C2C2C` with `rgba(22, 22, 22, 0.8)` in the theme files — this makes the window background translucent. (You may need to tweak other elements separately.)</samp>

## <samp>Wallpaper 🖼️</samp>

<samp>Hyprpaper is used to manage wallpapers.</samp>

## <samp>External libraries (quick list) 📦</samp>

<samp>These are external packages I commonly use, check each project's page for additional dependencies:</samp>

```bash
pwvucontrol
wpctl
ttf-fira-code-nerd
orchis-theme
hyprpaper
hyprpolkitagent
swaync
hyprpicker
```

## <samp>Notes 📝</samp>

- <samp>Most config files live in this repository under their respective folders (e.g. `waybar/`, `hypr/`, `kitty/`, `waybar/configs/`).</samp>
- <samp>If you want me to tidy or standardize any specific config (syntax, variables, or install scripts), tell me which one and I can update it.</samp>
