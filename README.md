# Gruvbox Light for Actual Budget

A light custom theme for [Actual Budget](https://actualbudget.org) based on the [Gruvbox](https://github.com/morhetz/gruvbox) color palette by Pavel Pertsev.

Warm, retro-groove tones — easy on the eyes, high readability.

## Installation

### From the catalog

Settings → **Theme** → **Custom theme**, then choose **Gruvbox Light** from the catalog. Custom themes no longer require an experimental feature flag.

### Manual

1. Copy the contents of [`actual.css`](./actual.css).
2. Open Settings → **Theme** → **Custom theme**.
3. Paste the CSS into **Custom theme CSS** and select **Apply**.
4. When updating an existing override, use the **Custom CSS is active** button to reopen the editor.

## Palette

| Role         | Color     |
|--------------|-----------|
| Background   | `#fbf1c7` |
| Foreground   | `#3c3836` |
| Accent       | `#af3a03` |
| Yellow       | `#d79921` |
| Red          | `#9d0006` |
| Green        | `#645f1c` |
| Blue         | `#076678` |

The theme maps all 237 current color tokens, including the redesigned sidebar, chart palettes, date ranges and alternating rows. Contrast tints are precomputed blends of Gruvbox colors so they remain compatible with Actual’s CSS validator.

Some component colors are outside the custom-theme variables, including syntax highlighting and generated chart labels. Active formula toggles reuse a primary background with bare-button text; one variable palette cannot make every conflicting use accessible. These limits need a separate upstream component change.

## Credits

- Palette: [Gruvbox](https://github.com/morhetz/gruvbox) by [Pavel Pertsev](https://github.com/morhetz) (MIT)
- CSS mapping: [Dakyne](https://github.com/Dakyne)

See also: [Gruvbox Dark for Actual Budget](https://github.com/Dakyne/gruvbox-dark-actualbudget).

## License

MIT — see [LICENSE](./LICENSE).
