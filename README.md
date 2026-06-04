# F1 2026 Analytics

A live Formula 1 analytics platform tracking the 2026 season.

**Live site:** https://f1-2026-analytics.netlify.app

## Features
- Interactive world map with all 22 circuit locations, route lines, and race status pins
- Live race results and podiums fetched from the Jolpica API
- Driver and constructor championship standings with real 2026 data
- Driver photos and team logos
- Sprint weekend toggle for sprint race results
- AI chat interface (coming soon)
- ML-powered race predictions (coming soon)

## Tech Stack
- Vanilla HTML/CSS/JavaScript — single file, no build step
- Leaflet.js with CartoDB Dark Matter tiles
- Jolpica API (Ergast F1 data)
- Deployed on Netlify

## Roadmap
- [ ] AI chat via Claude/Gemini API
- [ ] Tire degradation model (FastF1 + Python)
- [ ] Race winner prediction (XGBoost)
- [ ] Flask backend for ML models
- [ ] OpenF1 live race data integration

## Data Sources
- Race results & standings: [Jolpica API](https://api.jolpi.ca/ergast/f1)
- Driver/team images: Wikimedia Commons (CC / public domain)

---
Built by Harshith — ASU CS(AI) Sophomore
