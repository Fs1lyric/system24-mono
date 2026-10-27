# system24 mono

 the TUI-style Discord theme mono style.

- Pure black background with grey panels and white accents
- DM Mono at a light weight
- Square corners, square profile pictures, and labels on each panel
- Red is the only color, kept for mute, deafen and do not disturb

## Install

### Vencord / Vesktop / BetterDiscord

Download [`system24-mono.theme.css`](system24-mono.theme.css) and put it in your themes folder:

- Vesktop: `~/.config/vesktop/themes/`
- Vencord: `~/.config/Vencord/themes/`
- BetterDiscord: `~/.config/BetterDiscord/themes/`

Then turn it on under Settings → Themes.

### Online theme link

Paste this into Vencord's Online Themes:

```
https://raw.githubusercontent.com/Fs1lyric/system24-mono/main/system24-mono.theme.css
```

### Quick CSS

You can also paste the whole file into Settings → Vencord → Edit QuickCSS.

## Font

The theme uses [DM Mono](https://fonts.google.com/specimen/DM+Mono). Install it locally, or set `--font` and `--code-font` to `''` to use Discord's font.

## Customizing

Every option sits in the `body` and `:root` blocks at the top of the file. The colors are in `:root` under `/* color options */`.

## License

MIT. See [LICENSE](LICENSE).
