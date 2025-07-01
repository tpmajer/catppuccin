# Catppuccin for Ax-Shell

[Catppuccin](catppuccin.com) color schemes for [Ax-Shell](https://github.com/Axenide/Ax-Shell)

## Setup
1. Disable auto colors
![auto-color](./assets/auto-color.png)
2. Clone the repository and copy the css file as `colors.css` in `~/.config/Ax-Shell/styles/` and the .conf file as `colors.conf` in `~/.config/Ax-Shell/config/hypr/`
```bash
git clone https://github.com/claymorwan/catppuccin-ax-shell.git
cd catppuccin-ax-shell
rm ~/.config/Ax-Shell/styles/colors.css ~/.config/Ax-Shell/config/hypr/colors.conf
cp ./themes/css/<flavor>/colors-<accent>.css ~/.config/Ax-Shell/styles/colors.css
cp ./themes/hypr/<flavor>/colors-<accent>.conf ~/.config/Ax-Shell/config/hypr/colors.conf
```
3. Reload css or shell and hyprland

## Credit
- Color scheme by [Catppuccin](catppuccin.com)
- [Ax-Shell](https://github.com/Axenide/Ax-Shell) by [Axenide](https://github.com/Axenide)
