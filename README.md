# Digital Skills — V20 revised

Complete static GitHub Pages site with 11 Vega-Lite charts and local CSV datasets.

## What changed
- Chart 4 now explicitly compares adults without secondary school against the **overall Australian mean**, not against a second education group. The exact 2023/2025 observed scores and shortfalls are displayed.
- Chart 8 has a zero-centred diverging scale (−5 to +5); the Northern Territory is shown as −2.0, not silently clipped.
- Chart 9 uses 2021 share for circle area and the observed 2011–21 percentage-point gain for colour.
- Chart 10 uses a labelled **zoomed 68–82 index scale** rather than implying the colours cover the full 0–100 range.
- Chart 11, the conclusion, and responsive two-column layout are redesigned.
- Captions, sections, and source limitations are updated.

## Publishing
Upload index.html and all `charts/` and `data/` files to the repository root.

## Important limitation
The state polygons in Chart 10 are still fetched from `raw.githubusercontent.com` because the complete state GeoJSON was not available in the local workspace. This chart requires network access. The other map outline is local. The website relies on Vega libraries served from jsDelivr.

## Validation
JSON structure, local dataset existence and internally derived index-point differences are checked. Browser-based rendering must still be checked on the deployed site.
