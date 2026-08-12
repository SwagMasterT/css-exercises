# Block vs Inline Sizing

Block elements respect `width` and `height`. **Inline elements ignore width and height** — the properties simply have no effect unless you change the display type.

Three boxes below should be equal width and sit in a row. They're `<span>` elements (inline by default), so the width and height in the starter CSS aren't doing anything. Fix the layout using display and sizing properties.

## Self Check

- Three equal-width boxes appear in a horizontal row.
- All boxes share the same height.
- You changed `display` so that `width` and `height` take effect.
- You did not use flexbox, grid, or floats.
