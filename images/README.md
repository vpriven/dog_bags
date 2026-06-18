# Product images

Drop product photos here to replace the generated CSS/SVG art on the lineup cards.

Expected filenames (referenced from `index.html` product config):

| Product | Roll | Bag |
|---|---|---|
| Lemon | `lemon-roll.png` | `lemon-bag.png` |
| Fragrance-Free | `fragrance-free-roll.png` | `fragrance-free-bag.png` |

Notes:
- PNG with a transparent (or light) background works best — the card stage has a soft grey backdrop.
- Roughly square images look best; they're scaled to fit (`object-fit: contain`).
- If a file is missing, the card automatically falls back to the generated stripe illustration, so nothing breaks.

To add more products, give that product an `img: { roll, bag }` entry in the
`PRODUCTS` config in `index.html` and add the matching files here.
