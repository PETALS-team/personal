# PETALS Solo Check-in

A standalone static site (`index.html`, `privacy.html`; `compare.html` and
`result.html` are legacy-URL redirects) implementing a solo, shareable
version of the PETALS weekly check-in. It's a useful exercise on its own,
but the framework's real value comes from the team conversations it
unlocks — sharing your flower and comparing with a teammate.

## Colour palettes

Two distinct palettes are in play. Don't mix them up.

### Score palette (`COLORS` in index.html)

Used for the 1-5 rating dots and petal fills — colour encodes how good the
score is (red = struggling, green = thriving), independent of which factor
it belongs to.

| Score | Colour  | Hex       |
|-------|---------|-----------|
| 1     | Red-Orange | `#F24822` |
| 2     | Orange     | `#FFA629` |
| 3     | Yellow     | `#FFCD29` |
| 4     | Yellow-Green | `#BBCC00` |
| 5     | Green      | `#14AE5C` |

### Brand palette (`BRAND` in index.html)

Extracted from the five petal shapes in the PETALS logo mark. Each colour
is tied to a specific factor by the petal's clock position in the mark
(top = 12 o'clock), not to a score value. Use this palette for brand/UI
chrome and any content that references a specific factor by identity
(e.g. the intro's numbered steps) — never for score-intensity encoding.

| Colour | Clock position | Factor       | Hex       |
|--------|-----------------|--------------|-----------|
| Cyan   | 12 (top)        | Productivity | `#68CFB7` |
| Pink   | 2               | Enjoyment    | `#FF66C4` |
| Yellow | 4               | Teamwork     | `#FFDE59` |
| Green  | 8               | Learning     | `#C1FF72` |
| Purple | 10              | Serenity     | `#D8B4FE` |

## Content guidelines

- No references to the site's original "3rd anniversary" launch milestone,
  or any other date-specific/birthday framing — it dates the page.
- Frame the product as the **solo** version of PETALS throughout (title,
  header, copy). Keep the "useful alone, real value with a team" message
  in the intro and CTAs.
