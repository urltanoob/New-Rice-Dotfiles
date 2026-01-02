# Apps
- wpgtk
- firefox
- wofi
- hyprland
- waybar
- okular
- fzf
- bightnessctl
- btop
- kitty
- obsidian
- awww
- neovim
- networkmanager
- git
- fastfetch
- yay
# Wpgtk
Set theme according to image
```bash
wpg -s /home/urltanoob/.wallpaper
```

Initial setup
```bash
wpg-install.sh -gi
wpg -s /home/urltanoob/.wallpaper
gsettings set org.gnome.desktop.interface color-scheme 'prefer-dark'
gsettings set org.gnome.desktop.interface gtk-theme "FlatColor"
```

Add lines to .bashrc to have colors persist
```Config
(cat ~/.cache/wal/sequences &)
source ~/.cache/wal/colors-tty.sh
```
# Fonts
Jet-brains mono nerd font
```bash
yay -S ttf-jetbrains-mono-nerd
```

# Waybar
Just the config files
```bash
touch $HOME/.config/waybar/config.jsonc
touch $HOME/.config/waybar/style.css
```

Config
```Config

```

Style
```css

```

# AWWW
Set the image
```bash
awww img image.jpg --transition-type wipe
```

awww-daemon needs to be running but it is done within the hyprland config
```Config
exec-once = awww-daemon
```
