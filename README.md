# Digital Skills / Australia — revised GitHub Pages package (V14)

Contains `index.html`, 11 Vega-Lite JSON specifications, and all CSV/GeoJSON data.

## Upload
Upload the **contents** of this ZIP to the repository root. Keep the `charts/` and `data/` directories beside `index.html`, and replace any older files.

## What changed
- Full-width panels for complex plots and map comparisons so text/legends do not crowd.
- Chart 4 simplified from a nested chart to a clearly labelled 2023–2025 educational comparison.
- Consistent 0–100 index scale in heatmap; explicit source/measure distinctions.
- Map 9 uses proportional symbols plus rankings. Map 10 uses state-boundary choropleth plus rankings.
- Updated captions, spacing, and chapter colours.

## Limitations / checks
- **Not browser tested in this environment**; local syntax/data-path checks were completed.
- Chart 10 fetches Australian state boundary geometry from a public external repository. Verify this map loads after GitHub Pages deploys.
- Chart 2 and Chart 4 use two survey years only; they do not show an annual trend.
- Online Census response rates are not a measurement of digital ability.
- The rubric requires a public site, three map idioms, at least ten charts, source attribution and AI acknowledgement.
