# F1 2026 Analytics

A live Formula 1 analytics dashboard for the 2026 season, built with vanilla HTML/CSS/JS and hosted on Netlify.

**Live site:** https://f1-2026-analytics.netlify.app

---

## Features

- **Interactive Map** — All 22 circuits plotted on a live Leaflet.js map with race status, winners, and circuit info
- **Race Results** — Full race classifications and podiums for every completed round, pulled live from the Jolpica F1 API
- **Championship Standings** — Driver and constructor standings updated after each race
- **Podium Prediction** — Live ML-powered podium probability predictions via a Flask API (see [f1-2026-ml](https://github.com/hmaram-15/f1-2026-ml))
- **Countdown Timer** — Live countdown to the next race weekend

---

## Tech Stack

- Vanilla HTML, CSS, JavaScript — no frameworks
- [Leaflet.js](https://leafletjs.com/) — interactive circuit map
- [Jolpica F1 API](https://api.jolpi.ca/ergast/f1/) — race results, standings, qualifying data
- Netlify — static site hosting

---

## ML Integration

The Predictions tab connects to a live Flask API deployed on Render, serving an XGBoost podium prediction model trained on 2026 season data. The model uses grid position, qualifying gap to pole, constructor, and championship position as features.

See the ML repo for full details: [hmaram-15/f1-2026-ml](https://github.com/hmaram-15/f1-2026-ml)

---

## Data Sources

- Race results and standings: [Jolpica F1 API](https://api.jolpi.ca/ergast/f1/)
- Lap telemetry and tire data: [FastF1](https://docs.fastf1.dev/)
- Driver/team images: Wikimedia Commons (CC / public domain)

---

## Project Structure

```
index.html       # Entire frontend — single file
README.md
```
---

*Non-commercial personal project. All team logos, driver images and trademarks are property of their respective owners.*