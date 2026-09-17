# Color

## The blue

`#1E5197` — RGB `30, 81, 151`. Sampled from the Dei plate, then locked.

Use it as **paper**: full-bleed background on site and slides. Do not mix in `#254e92`, `#3a7ec8`, `#062a52`, `#c5d4e8`, `#7eb4e8`, `#0171A9`.

If a generator drifts, remap the field back to `#1E5197` in post. Do not “almost” match.

## Type whites

| Token | Hex | Use |
|---|---|---|
| W1 | `#FFFFFF` | Titles, numbers |
| W2 | `#F2F2F2` | Body, lists |
| W3 | `#E0E0E0` | Subtitles, secondary |
| W4 | `#C8C8C8` | Stamp `PANTHEON · MRG.IM`, footer, captions |

No grey-blue. No ink navy. Metal highlight on a figure may be pale grey; it is not a UI color.

## Cards / lines

Same plate. Border: 1px dashed W4. Fill: the plate, or at most 4% white mixed into `#1E5197`. No drop-shadow in another hue.

## Dark / light

There is no second theme. Site `html[data-theme=dark]` uses the same tokens.
