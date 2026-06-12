# Elon wealth scroll

Elon Musk's fortune as a horizontal strip where **1 pixel = $1,000** — no compressed scale. At ~$982 billion (Forbes, June 2026) the strip is 982 million pixels long, roughly 260 km of screen. Scroll it, drag it, or hit the turbo buttons; even at 10,000× auto-scroll the trip takes about 49 seconds.

Inspired by [1 Pixel Wealth](https://eattherichtextformat.github.io/1-pixel-wealth/).

## Run it

It's a single static file — open `index.html` in a browser, or serve it:

```bash
python3 -m http.server
```

To host on GitHub Pages: repo settings → Pages → deploy from `main`, root folder.

## Numbers

All figures as of June 2026, pre-SpaceX-IPO:

| Figure | Value | Source |
| --- | --- | --- |
| Net worth | $971B / $982B | Bloomberg Billionaires Index / Forbes |
| Median US full-time salary | ~$62,000/yr | BLS |
| Median US household net worth | $192,900 | Fed Survey of Consumer Finances 2022 |
| Top 1% wealth threshold | ~$11.6M | Federal Reserve data |
| Ending world hunger for a year | ~$40B | UN/WFP estimate |
| US homeless population | ~771,000 | HUD 2024 point-in-time count |

Some reference points (lifetime earnings, hunger cost) are widely cited approximations, not audited figures. The strip uses the Forbes number; update `TOTAL` in `index.html` when he crosses $1T.
