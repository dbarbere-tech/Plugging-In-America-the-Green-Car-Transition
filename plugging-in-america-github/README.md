# Plugging In America

A short visual investigation: what would it take to make every US car, truck and bus electric? It covers electricity demand, peak load, clean-power cost, total build-out cost, timeline, carbon impact, where EVs rank among net-zero projects, who can afford them today, how winter changes the picture, and whether parked cars could serve as grid batteries (vehicle-to-grid).

**Live page:** `https://<your-username>.github.io/<repo-name>/`

## Publish on GitHub Pages
1. Create a public repository and upload `index.html` (and this README).
2. Go to **Settings → Pages → Build and deployment**, set Source to *Deploy from a branch*, choose `main` and `/ (root)`, then click Save.
3. The page goes live at the URL above within a minute or two.

## Reproduce or extend it
- All chart numbers live in one JavaScript object, `const DATA`, near the bottom of `index.html`. Edit a value and reload; every chart redraws automatically.
- The **Download all chart data (CSV)** button exports every dataset.
- The **How this was made** section on the page lists each question asked of the AI assistant (Claude), the formula used, the key assumptions, and the primary sources (EIA, FHWA, NREL, Lazard, LBNL, EPA, Princeton Net-Zero America, KBB/Cox).
- No build step and no libraries: plain HTML, CSS and hand-drawn SVG.

## Limitations
These are order-of-magnitude estimates, not forecasts. The hourly demand curve is a stylized shape scaled to EIA's 2025 record peak, not measured data. For real hourly data, see the EIA Hourly Electric Grid Monitor (EIA-930).
