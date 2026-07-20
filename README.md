# St Andrew's Townsville faithful static replacement

A concept demo, not an official church website. Static HTML, CSS and JavaScript only.

## Run locally

Clone the repository then run `python3 -m http.server 8000` from the repository root. Open `http://localhost:8000/`. Do not use `file://`: browser storage, imports and relative route testing can behave differently.

## GitHub Pages

Deploy from `main` and `/` in GitHub Pages settings.

## Cloudflare Pages

Connect the repository or direct-upload this folder. Build command: none. Build output directory: `/`.

## Office PC

Run `python3 -m http.server 8000 --bind 0.0.0.0` from the repo root.

## Content backup and restore

Content is maintained directly in the HTML pages for this preservation-focused static demo.
