# Aeris

**Weather, beautifully simplified.**

A clean one-page weather app:

- **Live conditions** — current temperature, feels-like, condition, day high/low
- **Hourly forecast** — the next 24 hours with temperature, condition icons and rain probability
- **7-day forecast** — daily conditions, rain probability, and min–max temperature range bars
- **Detail cards** — rain chance (with today's max and rainfall so far), humidity, wind speed/direction/gusts, UV index now and today's max with plain-language guidance
- **Sunrise & sunset** — plus day length, in the place's own local time
- **Location search** — any city on Earth (Open-Meteo geocoding), plus a "my location" button
- **Advisories** — thunderstorm, heavy-rain, high-UV, strong-wind and extreme-heat notices generated from the forecast itself
- **Light & dark themes** — toggle in the corner; remembers your choice, follows your system by default. °C/°F toggle too

## Data & honesty notes

- All data comes from **Open-Meteo** (free, keyless, multi-model) fetched live in the visitor's browser; the last good response is cached so a temporary outage shows recent data with a note instead of a blank page.
- Advisories are **derived from forecast data, not official warnings** — the page says so, and points users to their national weather service (NiMet for Nigeria) for official alerts.

## How it works

One static page (`site/index.html`). No backend, no tracking, no accounts.

## Live

Published with GitHub Pages from this repo's `gh-pages` branch (the `site/` folder).
