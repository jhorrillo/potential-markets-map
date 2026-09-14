# Potential Markets, Old World 1800

Interactive map of potential market areas in the Old World circa 1800 (40 MJ energy budget).
One dot per market origin; hover previews the market polygon, click pins it and shows its statistics.

Live: https://jordanhorrillo.com/potential-markets-map/

- `index.html`: the map (MapLibre GL JS, CARTO Positron basemap).
- `data/origins.geojson`: one point per market with all attributes.
- `data/markets/<PREFIX>/<GRID_ID>.json`: one GeoJSON Feature per market, fetched on demand.
- `data/cities_index.{csv,json}`: cities of 20k or more with their market assignment.

Field definitions and the build pipeline live in the private build folder (`docs/DATA_SPEC.md`).
Data vintage: market layer 081826, populations 082626, cities 081426.
