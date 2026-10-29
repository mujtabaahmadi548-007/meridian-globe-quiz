# Meridian — 3D Globe Country Quiz

A guess-the-country game on a rotating 3D globe, built with three.js, d3-geo and topojson.

## Modes
- **Locate** – a country is named; click it on the globe.
- **Identify** – a country lights up; name it (multiple choice on Easy, typing with autocomplete on Medium/Hard).
- **Flags** – a flag is shown; click its country.
- **Explore** – no score; search or click any country for facts.

## Features
- Wrong guesses never reveal the answer: you get a distance clue (warm/cold) and keep trying, or skip and the answer stays hidden
- Each wrong try lowers the round's points
- 195 countries, 3 difficulty levels, region filter (World, Africa, Americas, Asia, Europe, Oceania), 5/10/20 rounds
- Speed and streak bonuses, paid hints, best scores saved in the browser
- Land, borders and coastlines are real 3D geometry and vector lines, so they stay sharp at any zoom
- Works with mouse, touch and keyboard (Enter = next, 1–4 = answer on Easy)

## Play
Open `index.html` in a browser, or enable GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/root`).

## Data
Borders: [world-atlas](https://github.com/topojson/world-atlas) (Natural Earth 1:10m, lightly simplified). Country facts: [world-countries](https://github.com/mledoze/countries). Flags: [flag-icons](https://github.com/lipis/flag-icons). All bundled inside `index.html`.
