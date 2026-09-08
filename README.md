# Cariplo 40 — Bratislava

Static one-page site for the Cariplo 40 Bratislava trip, styled with the Cariplo 40 logo palette.

## Contents

- `index.html` — the page (self-contained, all assets inlined)
- `cariplo-40-logo.svg`, `cariplo-40-logo-stacked.svg` — logo assets

## Viewing locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Publishing with GitHub Pages

1. Push this repository to GitHub (`origin` → `git@github.com:ginvidi/cariplo40.git`).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select the **`main`** branch and the **`/ (root)`** folder, then **Save**.
5. After the build completes, the site is available at:

   https://ginvidi.github.io/cariplo40/

GitHub Pages serves `index.html` from the repository root automatically.
