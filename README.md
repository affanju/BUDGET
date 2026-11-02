# Manage My Money

A simple personal budget app that runs in any browser. No sign-up, no server, no tracking.

## What it does

- **Budget** – income, expenses and savings, each shown weekly, fortnightly, monthly and yearly. Enter an amount and how often it's paid; the other columns calculate automatically. The summary shows total income, expenses, savings, cash balance and % of income spent.
- **Monthly tracker** – log daily income, bills and spending by date, category and the account it was paid from or into. Entries can be edited or deleted. Each entry is added to its category's total everywhere: the Budget tab shows spent and left this month for every item, and the tracker shows budget vs actual.
- **Ledger** – every entry for a month in date order, with money in, money out and a running balance for one account or all accounts together. A second running column shows how much of the month's forecast spending is left, and each expense shows what's left in its category. The summary includes a projected end-of-month balance.
- **Accounts** – add and edit your bank accounts, savings, cash, credit cards and loans. Shows each account's live balance (what's owed and available credit for cards), plus totals for money held, money owed and net balance.
- **Transfers** – use the "Transfer between accounts" entry type for credit card payments or moving money to savings. Both balances update and it isn't counted as spending.
- **Year forecast** – a January to December table and chart comparing your budget forecast with actual figures from the tracker, plus a year record of every category's total for each month.

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
