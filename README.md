# Daybook — Bahar daily planner

A personal planner web app: to-do, bills (with a bill scanner and explainer), groceries, goals, notes, stickers, a year countdown and a weather tile.

- `index.html` — the whole app (single file, no build step)
- `stickers/` — sticker and entrance images

## Run it
Open `index.html` in a browser, or serve the folder (`python3 -m http.server`).

## Publish on GitHub Pages
Push this folder to a repo, then Settings → Pages → deploy from the `main` branch root.

Note: the bill scanner and "ask about this bill" box use Claude through the Claude artifact runtime, so they only work when the app is opened as a Claude artifact. Everything else works anywhere. Data is saved in the browser (localStorage).
