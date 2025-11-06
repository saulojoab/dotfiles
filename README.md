[!center] # dotfiles ⚙️

A curated set of Arch Linux dotfiles and configuration for Hyprland, Waybar, Kitty, Nautilus and other desktop components.

## Table of contents

- Waybar 🧭
- App launcher — Walker 🚀
- File manager — Nautilus 📁
- Wallpaper — Hyprpaper 🖼️
- External libraries 📦

## Waybar 🧭

Configuration for Waybar is a modified version of:

https://github.com/UnFunnyGuy/hyprland-dots/tree/master/waybar

## App launcher — Walker 🚀

Walker is the launcher I use. Install it from the AUR:

```bash
yay -S walker-bin elephant elephant-providerlist elephant-desktopapplications
```

Enable the Elephant service:

```bash
elephant service enable
```

## File manager — Nautilus 📁

Nautilus is the default file manager in this setup.

Package:
https://archlinux.org/packages/extra/x86_64/nautilus/

Theme: Orchis-Dark

Install the theme and open the theme folder:

```bash
sudo pacman -S orchis-theme
code /usr/share/themes
```

Tip: to make the Orchis-Dark background slightly transparent you can replace occurrences of `#2C2C2C` with `rgba(22, 22, 22, 0.8)` in the theme files — this makes the window background translucent. (You may need to tweak other elements separately.)

## Wallpaper 🖼️

Hyprpaper is used to manage wallpapers.

## External libraries (quick list) 📦

These are external packages I commonly use, check each project's page for additional dependencies:

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

## Notes 📝

- Most config files live in this repository under their respective folders (e.g. `waybar/`, `hypr/`, `kitty/`, `waybar/configs/`).
- If you want me to tidy or standardize any specific config (syntax, variables, or install scripts), tell me which one and I can update it.
