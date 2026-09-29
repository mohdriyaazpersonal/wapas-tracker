# Wapas

Wapas is a private browser-based ledger for physical things you lend and borrow. Track the item, person, direction, expected return date, approximate value, notes, overdue state, and complete return history.

**Live website:** <https://mohdriyaazpersonal.github.io/wapas-tracker/>

## Run locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Data and privacy

Records are stored in the browser's `localStorage`. They do not sync automatically. Use **Backup & restore** before clearing browser data or changing devices.

## Publishing

This is a static website with no build step and is published from the `main` branch using GitHub Pages.
