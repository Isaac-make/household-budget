# Household budget

A private household budget tracker, published with GitHub Pages.

- The page code lives here (public).
- All money data is encrypted in the browser with the household passphrase and stored in a separate private repo. This repo never holds readable numbers.
- `prices.json` is refreshed from Yahoo Finance every 30 minutes on weekdays by `.github/workflows/prices.yml`. Add tickers to `tickers.json`.
