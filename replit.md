# Paulista Remap Chip — Agro Performance

## Overview
A single-page static website for Paulista Remap Chip, a Brazilian agricultural vehicle performance tuning company. The site is written in pure HTML/CSS/JS with no build system or dependencies.

## Project Structure
- `index.html` — The entire website (856 lines of HTML, CSS, and JS)
- `README.md` — Minimal project readme

## Running the App
The app is served using Python's built-in HTTP server on port 5000:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a **static** deployment with `publicDir: "."`.
