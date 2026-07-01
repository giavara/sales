# mentor — Sales proposals

Interactive HTML sales decks, one folder per lead, built on the [mentor design system](https://github.com/giavara/mentor-design).

- **Index:** https://giavara.github.io/sales/
- **Conidia:** https://giavara.github.io/sales/conidia/

## Structure

```
sales/
├── index.html      → landing that lists all proposals
├── assets/ fonts/  → brand assets for the index
└── conidia/        → self-contained deck (index.html + deck-stage.js + assets + fonts)
```

Each proposal folder is self-contained, so decks stay independent.

## Add a new proposal

1. Copy the `conidia/` folder, rename it (e.g. `bottega/`).
2. Edit the `<section>` blocks in its `index.html`.
3. Add a `.item` link in the root `index.html`.

## Navigate a deck

← / → arrows, PgUp/PgDn, Space, number keys, or tap left/right on touch. Press `R` to reset. Print → Save as PDF = one page per slide.

> ⚠️ Public repo — proposals contain pricing. Keep private or remove folders once deals close.
