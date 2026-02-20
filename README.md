# Japan + South Korea Autumn Trip Planner

Single-page itinerary and timetable planner for a 16-day Japan/Korea trip.

## What this project includes

- Interactive day-by-day itinerary (expand/collapse per day)
- Area filters (Japan, Korea, Tokyo, Kyoto, Seoul, etc.)
- Per-day 24-hour timetable with `View` / `Edit` modes
- Local autosave in browser storage
- JSON file workflows (`Connect`, `Save`, `Export`, `Import`)
- Local self-hosted heading font (`TASA Orbiter`)

## Project structure

```text
JapanKoreaTrip/
  index.html
  assets/
    images/
    fonts/
```

## Run locally

No build step is required.

1. Open `JapanKoreaTrip/index.html` directly in a modern browser.
2. Recommended: use Chromium-based browsers (Chrome/Edge) for direct file save support (`Connect JSON file`).

## Data behavior

- Timetable state is stored in `localStorage` under key `trip_timetable_state_v1`.
- When a JSON file is connected, updates can be saved directly and auto-saved.
- If direct file APIs are unavailable, use `Export JSON download` / `Import JSON file`.

## Font setup

- Headings use local `TASA Orbiter` via `@font-face`.
- Font file path used by the page: `assets/fonts/TASAOrbiter-VariableFont_wght.ttf`

## Notes

- This is a static HTML/CSS/JS project.
- No external dependencies are required for core functionality.
