# Manage My Money

A simple personal budget app that runs in any browser. No sign-up, no server, no tracking.

## What it does

- **Budget** – income, expenses and savings, each shown weekly, fortnightly, monthly and yearly. Enter an amount and how often it's paid; the other columns calculate automatically. The summary shows total income, expenses, savings, cash balance and % of income spent.
- **Monthly tracker** – log real income, bills and spending by date and category. Shows monthly totals and budget vs actual for each category.
- **Year forecast** – a January to December table and chart comparing your budget forecast with actual figures from the tracker.

## Your data

Everything is saved in the browser on the device you use (local storage). Nothing is sent anywhere.

- Use **Export backup** to save a `.json` file, and **Import backup** to load it on another device.
- Clearing your browser data will erase the app's data, so export a backup now and then.

## Put it on GitHub Pages

1. Create a new repository on GitHub (for example `manage-my-money`).
2. Upload all the files in this folder (Add file → Upload files), then commit.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute your app is live at `https://<your-username>.github.io/manage-my-money/`.

## Install it like an app

Open the GitHub Pages link on your phone:

- **Android (Chrome):** menu ⋮ → **Add to Home screen** / **Install app**.
- **iPhone (Safari):** Share → **Add to Home Screen**.

Once installed it opens full screen and works offline.

## Run it without GitHub

Download the folder and open `index.html` in a browser. Everything works except offline install, which needs a web address such as GitHub Pages.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | App name and icons for installing |
| `sw.js` | Offline support (bump `VERSION` after editing files) |
| `icon.svg`, `icon-192.png`, `icon-512.png` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve files as they are |
