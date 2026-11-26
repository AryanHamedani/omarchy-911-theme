# 911

A dark [Omarchy](https://omarchy.org) theme inspired by the latest Porsche 911 (`992.2`) night cockpit:
Race-Tex Charcoal surfaces, Ice Grey (`Crayon`) dial typography, Vanadium Grey trim, and a single
disciplined spark of Guards/Carmine Red for the full-width lightbar and tachometer redline.

Built for 10+ hour daily coding sessions: perceptually uniform OKLCH syntax hues, glare-free contrast
tuned to the APCA ergonomic band, and restrained chroma that eliminates red/blue chromostereopsis.

![911 on Omarchy](preview.png)

## Install

```bash
omarchy theme install https://github.com/AryanHamedani/omarchy-911-theme
```

Or open the menu: **Style → Theme → Install**, and paste the URL.

## Palette

![911 palette](docs/palette.png)

Every colour is drawn from Porsche's `992.2` Exclusive Manufaktur and Paint-to-Sample palette, calibrated in
OKLCH so no token jumps off the screen. Every readable text role — including comments and accents —
clears WCAG AA (4.5:1) on both the Race-Tex canvas and elevated Vanadium surfaces, with primary Ice Grey
text sitting at 12.9:1 to avoid halation.

| Role | Colour | Hex |
|---|---|---|
| Background | Race-Tex Charcoal | `#141619` |
| Elevated surface | Vanadium Grey | `#1d2026` |
| Text | Ice Grey (`Crayon`) | `#dadad6` |
| Bright text, cursor | Pure dial highlight | `#edede9` |
| Accent, focus | Guards / Carmine Red | `#e55c5a` |
| Selection | Slate Grey Neo trim | `#292d36` |
| Comments | Unlit dial markings | `#858a96` |
| red / orange / yellow | Carmine Red, Lava Orange, PCCB Racing Gold | `#e56c6a` `#e89158` `#e0be66` |
| green / cyan / blue | Oak Green Metallic Neo, Ice Glacier, Lugano Blue | `#7fb887` `#6ac4cb` `#6fa2de` |
| magenta / brown | Ultraviolet, Truffle Club Leather | `#b488cc` `#ad7f66` |

## Wallpapers

![911 wallpapers](docs/wallpapers.jpg)

Six `2560×1440` plate-free Porsche 911 (`992` / `992.2`) Precision Night Cockpit studies, mastered in 16-bit
with fine micro-grain dithering so shadows never band, and keyed to Race-Tex Charcoal (`#141619`), Ice Grey
(`#dadad6`), and 911 Guards/Carmine Red (`#e55c5a`). Cycle them with `omarchy theme bg next`. Four ship with
a 5-second intro that plays once when the theme or wallpaper is set, then settles on the still (turn intros
off with `omarchy theme bg intro disable`):

1. **Flyline monolith**: Vanadium Grey `992.2` Carrera GTS pure side profile over mirror-still obsidian under an Ice Grey light blade *(with intro)*
2. **GTS rain pavilion**: plate-free `992.2` Carrera GTS with vertical active cooling slats and 4-point HD Matrix LEDs on rain-slicked basalt before dark board-formed concrete *(with intro)*
3. **Nordic fjord dusk**: dark basalt `992` on wet volcanic sea cliffs at deep Lugano Blue twilight *(with intro)*
4. **992.2 digital cockpit**: driver's-eye curved five-tube digital cluster behind a Race-Tex wheel looking out into misty midnight rain *(with intro)*
5. **GTS alpine twilight**: Vanadium Grey `992.2` Carrera GTS with center dual exhausts carving a wet Dolomites hairpin at last light
6. **Kinetic alpine tunnel**: rolling-rig `992` sweeping through curved dark concrete and warm Lava Orange light ribs

## What's themed

From `colors.toml`, through Omarchy's own templates: terminals (Alacritty, Foot, Ghostty,
Kitty), Neovim, VS Code, Helix, the Omarchy shell and bar, the lock screen, Chromium, tmux,
GNOME apps and more. On top of that, **911** ships:

- **btop**: graphs that sweep like a `992.2` tachometer, Oak Green Metallic Neo → PCCB Racing Gold → Guards/Carmine Red.
- **Window borders**: a smoked Carmine lightbar gradient on the focused window that melts into dark graphite.
- **Icons**: Yaru Red Dark (matching the 911 brake calipers and rear lightbar).
- **Boot unlock screen**: the Omarchy wordmark in 911 Guards/Carmine Red, via **Style → Unlock** in the Omarchy menu.

## 36-App Companion Suite

Looking for standalone **911 (`992.2`)** themes for tools beyond Omarchy's built-in templates? See [**`AryanHamedani/911-themes`**](https://github.com/AryanHamedani/911-themes) — 36 deeply crafted, WCAG AA verified ports built directly from this repository's `colors.toml`:

- **Editors & Notes:** Neovim (LazyVim + full plugin suite), VS Code / Antigravity IDE, Obsidian
- **Browsers & Desktop:** Zen Browser, Telegram Desktop (617 keys + flyline wallpaper), Chromium, GTK 3/4, Hyprland, Share Picker, Fcitx5, imv, mpv
- **Terminals & Shells:** Foot, Ghostty, Alacritty, Kitty, Herdr, tmux, Starship, Atuin, fzf, zsh-syntax-highlighting
- **CLI & TUI Tools:** K9s, kubecolor, Lazygit, Lazydocker, Delta, bat, eza, pgcli, OpenCode, Claude Code, Pi, Cliamp, Fastfetch, btop

## Credits

All six wallpapers were art-directed and generated from real Porsche 911 (`992` / `992.2`) reference
photography using Higgsfield (`Seedream 5.0 Flash`) and Antigravity, then graded and mastered in 16-bit
to `2560×1440` with fine micro-grain dithering.

Not affiliated with or endorsed by Porsche AG. Porsche and 911 are trademarks of Porsche AG.

## License

[MIT](LICENSE)
