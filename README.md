# Dark Pastel for Zed

A dark theme for [Zed](https://zed.dev/) inspired by [iTerm2's Dark Pastel](https://github.com/mbadolato/iTerm2-Color-Schemes#dark-pastel) color scheme, featuring vibrant pastel colors on a pure black background.

## Installation

### Via Extensions

> **Note:** This theme is not yet published to the Zed extension marketplace.

Once published, you will be able to search for "Dark Pastel" in Zed's extension panel.

### Manual Installation (Local Theme)

1. Create the themes directory if it doesn't exist:
   ```bash
   mkdir -p ~/.config/zed/themes
   ```

2. Download the theme file:
   ```bash
   curl -o ~/.config/zed/themes/dark_pastel.json \
     https://raw.githubusercontent.com/shiroemons/zed-dark-pastel/main/themes/dark_pastel.json
   ```

3. Select the theme in Zed:
   - Open Command Palette (`Cmd+Shift+P` on macOS, `Ctrl+Shift+P` on Linux)
   - Type "theme" and select "zed: Open Theme Selector"
   - Choose "Dark Pastel"

### Dev Extension Installation (For Contributors)

If you want to develop or modify the theme:

1. Install [Rust](https://www.rust-lang.org/tools/install) if not already installed

2. Clone this repository:
   ```bash
   git clone https://github.com/shiroemons/zed-dark-pastel.git
   ```

3. Install as dev extension in Zed:
   - Open Command Palette (`Cmd+Shift+P` on macOS, `Ctrl+Shift+P` on Linux)
   - Type "zed: Install Dev Extension"
   - Select the cloned repository directory

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Background | #000000 | Main background |
| Foreground | #FFFFFF | Text |
| Red | #FF5555 | Strings, errors |
| Green | #55FF55 | Properties, success |
| Yellow | #FFFF55 | Keywords, warnings |
| Blue | #4488FF | Functions |
| Magenta | #FF55FF | Constants, numbers |
| Cyan | #55FFFF | Types, info |

## Credits

- Color scheme inspired by [Dark Pastel](https://github.com/mbadolato/iTerm2-Color-Schemes#dark-pastel) from [iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes) by [@mbadolato](https://github.com/mbadolato)
- Built for [Zed](https://zed.dev/), a high-performance, multiplayer code editor

## Related

- [iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes) - The original color scheme collection
- [Zed Theme Documentation](https://zed.dev/docs/themes) - Official Zed theming guide
- [Zed Extension Development](https://zed.dev/docs/extensions/developing-extensions) - Guide for extension developers

## License

[MIT](LICENSE)
