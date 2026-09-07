# Decision Coin

An over-engineered coin flip for the chronically indecisive. Name your two options, load the coin if you want to admit your bias out loud, and let it decide — with a full flip history and a streak tracker to keep you honest about how "random" your luck has actually been.

## Description

Decision Coin is a single-file HTML app for settling two-option decisions ("order in" vs "cook", "yes" vs "no", "left" vs "right") without agonizing. Unlike a real coin, this one lets you configure the odds, so you can be transparent about wanting an 80% chance of "order in" instead of pretending it's a fair fight.

Features:
- **Custom labels** — rename both sides of the coin to whatever you're deciding between
- **Configurable weight** — bias the flip anywhere from 1% to 99% per side, with a live readout and a "this coin is loaded" flag when it's off 50/50
- **Animated flip** — a 3D coin flip with randomized landing side
- **Streak tracking** — current streak and longest streak of the same outcome in a row
- **Session history** — a running log of every flip with the outcome and timestamp

## Visuals

Botanical-dark palette: deep green background, parchment text, copper/gold accent for the coin faces. Fraunces for display type, Inter for UI text, IBM Plex Mono for data labels and stats — consistent with the rest of the single-file build series.

## Installation

No build step, no dependencies to install. Two files:
- `decision-coin.html` — the app
- `README.md` — this file

Open `decision-coin.html` directly in any modern browser, or drop it on any static host (Vercel, Netlify, GitHub Pages) as-is.

## Usage

1. Open `decision-coin.html`.
2. Edit the two side labels to match your decision.
3. Optionally drag the bias slider away from 50/50 if you want the coin loaded.
4. Press "Flip the coin."
5. Watch your streak and history build as you flip.

Flip history is kept in memory for the current session only — refreshing the page clears it.

## Support

This is a personal single-file build with no dedicated support channel. Open the HTML file in a text editor to tweak colors, fonts, or copy directly.

## Roadmap

Possible future additions:
- Export flip history as CSV
- More than two sides (weighted die mode)
- Shareable "loaded coin" configs via URL params

## Contributing

Personal project, not currently open to outside contributions.

## Authors and acknowledgment

Built by Soundarya as part of an ongoing series of single-file HTML creative tools.

## License

Personal project — no license specified.

## Project status

Complete for a first pass. Open to iteration if a real use case demands more (weighted dice, export, etc.).
