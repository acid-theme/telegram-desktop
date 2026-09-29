# Acid for Telegram Desktop

Three flavours: **Acetic** (`#000000`), pure black with vibrant accents; **Citric** (`#1c1b19`), warm dark grey with muted accents; and **Lactic** (`#ffffff`), white with accents darkened to match.

Part of [Acid](https://github.com/acid-theme/acid), a very dark colourscheme in two
flavours. The main README lists the other ports.

## Install

```sh
curl -fsSLO \
  https://raw.githubusercontent.com/acid-theme/telegram-desktop/main/acid-acetic.tdesktop-palette
```

Open the file with Telegram Desktop, or in Telegram: **Settings → Chat Settings
→ Theme → Edit theme**, then load it.

All 586 of Telegram's palette entries are set. A partial palette would leave the
rest on Telegram's light defaults, so completeness is the point rather than a
nicety.

Telegram's source palette allows a `value | fallback` form that its theme parser
refuses, so only the value is kept.

The palette is built from Telegram's own default by transformation: neutral
colours are mapped onto the Acid neutral ramp by inverted lightness, so the
layering its designers encoded survives, and saturated colours snap to the
nearest Acid accent. Entries that reference another entry upstream still do.

## Files

- `acid-acetic.tdesktop-palette`
- `acid-citric.tdesktop-palette`
- `acid-lactic.tdesktop-palette`

## Generated

Acid 0.1.0, rendered by acidify from
[`ports/telegram-desktop/acid.palette.tera`](https://github.com/acid-theme/acid/blob/main/ports/telegram-desktop/acid.palette.tera).
Edits to these files are overwritten on the next release. Report issues on
[acid-theme/acid](https://github.com/acid-theme/acid/issues).

## Licence

MIT.
