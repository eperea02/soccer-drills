# Youth Soccer Drills

A simple static site listing practice drills and games. Built with plain HTML/CSS — no build tools required, so it's ready to publish as-is with GitHub Pages.

## Structure

- `index.html` — home page with the drill library and a sample practice plan
- `styles.css` — shared styling for all pages
- `drills/` — one HTML page per drill/game

## Adding a new drill

1. Copy an existing file in `drills/` as a starting point.
2. Update the title, tags, and content.
3. Add a card linking to it from the `#drills` section in `index.html`.

## Publishing

This site is designed to be served directly by GitHub Pages from the repository root (no build step) — see the setup walkthrough for enabling Pages in the repo settings.
