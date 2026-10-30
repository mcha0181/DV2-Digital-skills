# Australia's Digital Divide — V13

11 Vega-Lite charts in a publicly hosted single page. V13 is an evidence-led redesign using **only the project source data** (ADII 2025 and ABS Census); no invented observations.

## Upload
Unzip. Replace the repository-root `index.html`, all `charts/` files, and maintain `data/`. GitHub Pages must serve from root (`main` branch). Check maps and charts after deployment.

## Design updates
- Chart 1: one blue bar colour for every state; reference benchmark.
- Chart 2: 3 groups and two year endpoints with numeric labels.
- Charts 3–4: separate age and education contrasts; no extrapolated time series.
- Maps 2–3: actual geographic symbol map and choropleth with side rankings. Distinct map idioms.
- Ending: 100% stacked bars for digital exclusion with all included shares; three groups.
- Coloured chapter backgrounds, clearer editorial copy and reduced empty space.

**Data cautions:** ability (index points) and online Census participation (percent) are not interchangeable. Education and employment associations do not demonstrate causation. The digital exclusion populations overlap. Geographic choropleth references public state-boundary GeoJSON via `charts/chart10.json`; verify the URL still responds.

**AI acknowledgement** is retained in the website footer. The provided JSON is syntactically checked, but actual browser rendering is not guaranteed.
