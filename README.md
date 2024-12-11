# helix-epd-theme
Color scheme for use with Helix Editor on e-ink devices

## Instructions
- Place `e-ink.toml` in `~/.config/helix/themes`
- To `~/.config/helix/config.toml`, add the following (I have this placed at the very top, above `[editor]`): `theme = "e-ink"`

## Notes
The UI looks satisfying, but pseudo-syntax highlighting (i.e., using italics, underlines and only grayscale) could be improved. Markdown looks downright ugly at the moment; changes coming.


Terminal emulators may vary in their own themes, potentially confounding things. The colors section of my alacritty config is as follows:
```
[colors]
draw_bold_text_with_bright_colors = true

[colors.bright]
black = "#000000"
blue = "#555555"
cyan = "#555555"
green = "#555555"
magenta = "#555555"
red = "#555555"
white = "#888888"
yellow = "#555555"

[colors.cursor]
cursor = "#000000"
text = "#ffffff"

[colors.normal]
black = "#000000"
blue = "#444444"
cyan = "#444444"
green = "#444444"
magenta = "#444444"
red = "#313131"
white = "#53565b"
yellow = "#444444"

[colors.primary]
background = "#ffffff"
foreground = "#000000"
```
