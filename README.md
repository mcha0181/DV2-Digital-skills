# Digital Skills DV2 — V18 editorial/quality revision

This ZIP is ready to upload as the contents of a GitHub repository, with `index.html` in the root and `charts/` and `data/` beside it.

## Improvements
- Chart 2 uses a small, explicit, precomputed three-group table: two observation years, no invented intermediates.
- Chart 4 uses a directly labelled two-year heatmap rather than suggesting a continuous trend.
- Chart 11 has a clearer, accessible 100-person pictograph comparison with its own legend.
- Chart 10 legend explicitly uses a continuous 0–100 colour scale; the source is still an external state GeoJSON.
- Stronger editorial section colour, chart backgrounds, and evidence-led captions.

## Required final checks
1. Publish `index.html`, every JSON chart, and every CSV file.
2. In a private browser window check all 11 Vega-Lite charts (especially Chart 10, which depends on an external shape source).
3. Test the dropdowns, tooltips and small-screen layout.
4. Keep a short, accurate source and AI acknowledgement for FIT3179.

**Important:** This revision was inspected for JSON correctness and local data dependencies, but a successful live Chromium rendering test was not available in this environment. No grade can be guaranteed.
