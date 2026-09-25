# Dinner plan PWA

Weekly batch-cook dinner plan, recipes and shopping list. Works offline once opened.

## Deploy on GitHub Pages
1. Create a new repo (e.g. `dinners`) and upload every file and the `icons/` folder to the repo root.
2. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
3. Open `https://<your-username>.github.io/dinners/` on your phone after a minute or two.

## Install on the phone
- iPhone (Safari): Share → Add to Home Screen.
- Android (Chrome): menu → Install app / Add to Home screen.

## Updating the plan
Edit the `DAYS`, `RECIPES` and `SHOP` blocks in `index.html`, then bump `VERSION` in `sw.js`
(e.g. `dinners-v2`) so installed phones fetch the new version. Shopping ticks are stored on
the device; change `KEY` in `index.html` for a new week to start with a clean list.
