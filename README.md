# mentor — Sales proposals

Interactive HTML sales decks, one folder per lead, built on the [mentor design system](https://github.com/giavara/mentor-design).

There is **no index page** — the root URL (`/`) returns 404 on purpose. Each deck is reachable only via its direct link, shared privately with the lead.

## Structure

```
sales/
└── <lead>/         → self-contained deck (index.html + deck-stage.js + assets + fonts)
```

Each folder is independent.

## Add a new proposal

1. Copy an existing lead folder, rename it.
2. Edit the `<section>` blocks in its `index.html`.
3. Share only the direct link: `https://giavara.github.io/sales/<lead>/`.

## Navigate a deck

← / → arrows, PgUp/PgDn, Space, number keys, or tap left/right on touch. Press `R` to reset. Print → Save as PDF = one page per slide.

> ⚠️ Public repo — decks contain pricing. Keep private or remove folders once deals close.
