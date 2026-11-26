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
| Accent, focus, cursor | Guards / Carmine Red | `#e55c5a` |
| Selection | Slate Grey Neo trim | `#292d36` |
| Comments | Unlit dial markings | `#858a96` |
| red / orange / yellow | Carmine Red, Lava Orange, PCCB Racing Gold | `#e56c6a` `#e89158` `#e0be66` |
| green / cyan / blue | Oak Green Metallic Neo, Ice Glacier, Lugano Blue | `#7fb887` `#6ac4cb` `#6fa2de` |
| magenta / brown | Ultraviolet, Truffle Club Leather | `#b488cc` `#ad7f66` |

## Wallpapers

![911 wallpapers](docs/wallpapers.jpg)

Six 4K (`3840×2160`) modern 911 (`992` / `992.2`) night and studio studies, all keyed to Race-Tex Charcoal,
Vanadium Grey, Ice Grey, and Carmine Red. Cycle them with `omarchy theme bg next`. Four ship with a 5-second
intro that plays once when the theme or wallpaper is set, then settles on the still (turn intros off with
`omarchy theme bg intro disable`):

1. **Flyline eclipse**: chiaroscuro 992 side profile mirrored in still black glass under an Ice Grey light blade *(with intro)*
2. **GTS Vanadium studio**: `992.2` 911 Carrera GTS in Vanadium Grey Metallic showcasing vertical active aero flaps and 4-point HD Matrix LEDs *(with intro)*
3. **Nordic fjord dusk**: volcanic sea cliffs, drifting mist, Lugano Blue twilight, and a full-width Carmine lightbar *(with intro)*
4. **GTS lightbar study**: `992.2` 911 Carrera GTS rear three-quarter close-up highlighting the sculpted full-width Carmine LED bar and twin central exhausts *(with intro)*
5. **Dolomites last light**: sweeping alpine switchback beneath jagged spires catching the last ember of alpenglow
6. **Kinetic alpine tunnel**: rolling-rig motion through curved board-formed concrete and warm Lava Orange light ribs

## What's themed

From `colors.toml`, through Omarchy's own templates: terminals (Alacritty, Foot, Ghostty,
Kitty), Neovim, VS Code, Helix, the Omarchy shell and bar, the lock screen, Chromium, tmux,
GNOME apps and more. On top of that, **911** ships:

- **btop**: graphs that sweep like a `992.2` tachometer, Oak Green Metallic Neo → PCCB Racing Gold → Guards/Carmine Red.
- **Window borders**: a smoked Carmine lightbar gradient on the focused window that melts into dark graphite.
- **Icons**: Yaru Red Dark (matching the 911 brake calipers and rear lightbar).
- **Boot unlock screen**: the Omarchy wordmark in 911 Guards/Carmine Red, via **Style → Unlock** in the Omarchy menu.

## Credits

The `992.2` studio wallpapers are graded and mastered to 4K (`3840×2160`) from official Porsche Newsroom
press photography; the nocturnal driving studies were art-directed and generated from real Porsche 911
reference photography using Higgsfield (`Seedream 5.0 Flash`) and Antigravity, then graded and mastered to 4K.

Not affiliated with or endorsed by Porsche AG. Porsche and 911 are trademarks of Porsche AG.

## License

[MIT](LICENSE)
