# PaperColor Theme for Zed

A clean, elegant theme for the Zed editor inspired by the texture and feel of paper. This theme provides both light and dark variants with carefully chosen colors that are easy on the eyes and optimized for long coding sessions.

## Features

- **Light and Dark variants** - Switch between themes based on your preference or system settings
- **Paper-inspired design** - Clean, minimal aesthetic that reduces eye strain
- **Syntax highlighting** - Thoughtfully designed colors for better code readability
- **Terminal support** - Consistent theming across the integrated terminal
- **Accessibility focused** - High contrast ratios for better readability

## Installation

### From Zed Extensions (Recommended)

1. Open Zed
2. Press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Linux/Windows) to open the command palette
3. Type "zed: extensions" and press Enter
4. Search for "PaperColor"
5. Click "Install" next to the PaperColor theme

### Manual Installation

1. Clone this repository or download the files
2. Open Zed
3. Press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Linux/Windows)
4. Type "zed: extensions" and press Enter
5. Click "Install Dev Extension" in the top right
6. Select the `papercolor-zed` directory

## Usage

After installation:

1. Open Zed settings with `Cmd+,` (macOS) or `Ctrl+,` (Linux/Windows)
2. Or use the command palette: `zed: open settings`
3. Add one of the following to your settings:

```json
{
  "theme": "PaperColor Light"
}
```

or

```json
{
  "theme": "PaperColor Dark"
}
```

### Auto-switching between light and dark

You can also configure Zed to automatically switch between light and dark variants based on your system settings:

```json
{
  "theme": {
    "mode": "system",
    "light": "PaperColor Light",
    "dark": "PaperColor Dark"
  }
}
```

## Theme Preview

### Light Theme
The light variant features:
- Clean white/off-white backgrounds
- Dark text for excellent readability
- Subtle syntax highlighting with carefully chosen accent colors
- Minimal visual noise

### Dark Theme
The dark variant features:
- Deep, comfortable dark backgrounds
- Light text that's easy on the eyes
- Vibrant but not overwhelming syntax highlighting
- Perfect for low-light environments

## Color Palette

### Light Theme Colors
- **Background**: `#eeeeee` (Light gray, paper-like)
- **Foreground**: `#444444` (Dark gray text)
- **Accent**: `#005f87` (Deep blue)
- **String**: `#008700` (Green)
- **Keyword**: `#8700af` (Purple)
- **Comment**: `#878787` (Muted gray)

### Dark Theme Colors
- **Background**: `#1c1c1c` (Dark gray)
- **Foreground**: `#d0d0d0` (Light gray text)
- **Accent**: `#87d7ff` (Light blue)
- **String**: `#5fff5f` (Bright green)
- **Keyword**: `#d787ff` (Light purple)
- **Comment**: `#808080` (Muted gray)

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues:

1. Fork this repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Issues

If you encounter any problems or have feature requests, please [open an issue](https://github.com/yourusername/papercolor-zed/issues) on GitHub.

## License

This theme is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the original [PaperColor theme for Vim](https://github.com/NLKNguyen/papercolor-theme) by NLKNguyen
- Built for Zed editor version 0.198.5 and later
- Thanks to the Zed community for their excellent documentation and tools

---

**Enjoy coding with PaperColor!** 📝✨