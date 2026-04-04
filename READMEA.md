# York Street Music Fest — Event Center Website

A 5-page static website for the York Street Music Fest event center.

## Pages

| File | Description |
|------|-------------|
| [home-page.html](home-page.html) | Landing page: hero section, artist preview (6 cards), newsletter form |
| [about.html](about.html) | Mission statement, photo carousel (4 slides), embedded Google Map |
| [lineup.html](lineup.html) | Full artist grid (10 cards), search bar, filter tags, grid/list toggle |
| [schedule.html](schedule.html) | Event table (Artist/Stage/Time/Day) with filter buttons |
| [contact.html](contact.html) | Contact form (email, name, message) |

## Running Locally

Open any `.html` file directly in a browser, or serve with:

```bash
python3 -m http.server 8000
```

No build steps, dependencies, or package manager required.

## Tech Stack

- **HTML/CSS** — no framework or build tooling
- **Fonts:** Outfit & Roboto Mono via Google Fonts CDN
- **Icons:** Font Awesome 6

## Design Tokens

| Variable | Value | Usage |
|----------|-------|-------|
| `--primary-100` | `#00FF84` | Neon green accent |
| `--primary-200` | `#03C365` | Mid green |
| `--primary-300` | `#068747` | Dark green |
| `--black-800` | `#0C0F0A` | Background |
| `--white-100` | `#FFFFFF` | Text / light elements |

## Assets

Images are in the [images/](images/) directory, organized by subdirectory:

- `hero/` — hero section backgrounds
- `artist/` — artist1–10.jpg
- `festival-photos/` — marketing-photos1–4.jpg
- `about/` — about page images
- `location/` — venue/map images
- `footer/` — footer assets
