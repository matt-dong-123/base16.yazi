# Base16 Yazi Flavor

A Yazi flavor using standard terminal base16 color names (black, red, green, yellow, blue, magenta, cyan, white, gray, and their light variants).

## Installation

```bash
# Clone into your yazi flavors directory
git clone https://github.com/yourusername/base16.yazi ~/.config/yazi/flavors/base16.yazi
```

## Usage

Add to your `~/.config/yazi/theme.toml`:

```toml
[flavor]
dark = "base16"
light = "base16"
```

## Color Mapping

This flavor uses standard terminal colors:

| Purpose | Color |
|---------|-------|
| Directories | blue |
| Executables | green |
| Symlinks | gray |
| Orphans | white |
| Images | cyan |
| Media | yellow |
| Archives | magenta |
| Documents | green |
| Markers (copy) | green |
| Markers (cut) | red |
| Markers (select) | yellow |
| Border | gray |
| Active tab | blue on black |
| Inactive tab | blue on darkgray |

## License

MIT
