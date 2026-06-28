# sangre-negra.yazi

A dark theme for [Yazi](https://github.com/sxyazi/yazi) built around a **pure black and blood red** palette. No pastels, no Catppuccin, no generic colors.

## Colors

| Element | Color |
|---|---|
| Directories | Wine red `#8b0000` |
| Text and code files | Wine red `#8b0000` |
| Executables | Blood red `#c0392b` |
| Archives | Bright red `#c0392b` |
| Images | Brown `#a0522d` |
| Audio / Video | Dark red `#922b21` |
| Background | Pure black |

## Requirements

- [Yazi](https://github.com/sxyazi/yazi) v0.2.4 or higher
- A [Nerd Font](https://www.nerdfonts.com/) installed in your terminal

## Installation

```bash
# Create the flavors folder if it doesn't exist
mkdir -p ~/.config/yazi/flavors

# Clone the repository
git clone https://github.com/pitertapia884-commits/sangre-negra.yazi ~/.config/yazi/flavors/sangre-negra.yazi
```

Then edit your `~/.config/yazi/theme.toml` and add:

```toml
[flavor]
dark  = "sangre-negra"
light = "sangre-negra"
```

Restart Yazi and you're done.

## Uninstall

Remove the flavor folder and delete the lines from `theme.toml`:

```bash
rm -rf ~/.config/yazi/flavors/sangre-negra.yazi
```
