# Base16 Yazi Flavor

A pair of dark/light Yazi flavors using standard terminal base16 color names (black, red, green, yellow, blue, magenta, cyan, white, gray, and their light variants).

## Installation

### Manual

```bash
# Clone into your yazi flavors directory
git clone https://github.com/matt-dong-123/base16.yazi ~/.config/yazi/flavors
```

### `ya` pkg manager

```bash
ya pkg add matt-dong-123/base16:base16-dark
ya pkg add matt-dong-123/base16:base16-light
```

## Usage

Add to your `~/.config/yazi/theme.toml`:

```toml
[flavor]
dark = "base16-dark"
light = "base16-light"
```

## License

MIT
