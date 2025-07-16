# Catppuccin for end-4's shell

[Catppuccin](catppuccin.com) color schemes for [end-4 shell](https://github.com/end-4/dots-hyprland)

## Setup
1. Disable auto colors in the settings app in Advanced
2. Clone the repository and copy the json file as `colors.json` and the .scss file as `material_colors.scss` in `~/.local/state/quickshell/user/generated`
```bash
git clone https://github.com/claymorwan/catppuccin
cd catppuccin/end-4
rm ~/.local/state/quickshell/user/generated/colors.json ~/.local/state/quickshell/user/generated/material_colors.scss
cp ./themes/json/<flavor>/colors-<accent>.json ~/.local/state/quickshell/user/generated/colors.json
cp ./themes/hypr/<flavor>/material_colors-<accent>.scss /home/claymorwan/.local/state/quickshell/user/generated/material_colors
```
3. Reload the shell

## Credit
- Color scheme and Whiskers by [Catppuccin](catppuccin.com)
- [end-4 Shell](https://github.com/end-4/dots-hyprland) by [end-4](https://github.com/end-4)
