# Ghostty HackTheBox Theme

This is a **Ghostty** theme inspired by the HackTheBox color scheme used in Windows Terminal. It provides a vivid and consistent set of colors for your command-line experience.

[About Ghostty Themes](https://ghostty.org/docs/features/theme)

## Preview

| **Color**        | **Hex**    | **Usage**         |
|------------------|------------|-------------------|
| Black            | `#000000`  | palette index 0   |
| Red              | `#FF8484`  | palette index 1,9 |
| Green            | `#C5F467`  | palette index 2,10|
| Yellow           | `#FFCC5C`  | palette index 3,11|
| Blue             | `#5CB2FF`  | palette index 4,12|
| Purple           | `#CF8DFB`  | palette index 5,13|
| Cyan             | `#3A96DD`  | palette index 6   |
| White            | `#c5d1EB`  | palette index 7   |
| Bright Black     | `#A4B1CD`  | palette index 8   |
| Bright Cyan      | `#61D6D6`  | palette index 14  |
| Bright White     | `#F2F2F2`  | palette index 15  |

## Installation

1. Open the `~/.ghostty` (or your relevant Ghostty config file).
2. Replace your current color definitions with the code block below.
3. Restart or reload Ghostty to see the changes take effect.

## Theme Config

```ini
# Ghostty HackTheBox Theme

palette = 0=#000000
palette = 1=#FF8484
palette = 2=#C5F467
palette = 3=#FFCC5C
palette = 4=#5CB2FF
palette = 5=#CF8DFB
palette = 6=#3A96DD
palette = 7=#c5d1EB
palette = 8=#A4B1CD
palette = 9=#FF8484
palette = 10=#C5F467
palette = 11=#FFCC5C
palette = 12=#5CB2FF
palette = 13=#CF8DFB
palette = 14=#61D6D6
palette = 15=#F2F2F2
background = #141D2B
foreground = #c5d1EB
cursor-color = #FFFFFF
cursor-text = #141D2B
selection-background = #FFFFFF
selection-foreground = #000000
