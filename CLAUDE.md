# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static HTML/CSS website for **York Street Music Fest** — a 5-page event center site with no build tooling or JavaScript framework.

## Running Locally

Open any `.html` file directly in a browser, or serve with:

```bash
python3 -m http.server 8000
```

No build, lint, or test commands exist.

## Architecture

**Pages:**
- [home-page.html](home-page.html) — Landing page: hero, artist preview (6 cards), newsletter form
- [about.html](about.html) — Mission, photo carousel (4 slides), embedded Google Map
- [lineup.html](lineup.html) — Full artist grid (10 cards), search bar, filter tags, grid/list toggle
- [schedule.html](schedule.html) — Event table (Artist/Stage/Time/Day), filter buttons
- [contact.html](contact.html) — Contact form (email, name, message)

All pages share an identical fixed header (YS logo + nav) and footer (Font Awesome social icons).

## Design System

**CSS variables** defined in [style.css](style.css):
- `--primary-100`: #00FF84 (neon green accent)
- `--primary-200`: #03C365
- `--primary-300`: #068747
- `--black-800`: #0C0F0A
- `--white-100`: #FFFFFF

**Fonts (Google Fonts CDN):** Outfit (primary), Roboto Mono (secondary)

**Icons:** Font Awesome 6 via `https://kit.fontawesome.com/8d9931e63d.js`

## Assets

Images live in [images/](images/) with subdirectories: `hero/`, `artist/` (artist1–10.jpg), `festival-photos/` (marketing-photos1–4.jpg), `about/`, `location/`, `footer/`. HTML references them with root-relative paths (`/images/...`).
