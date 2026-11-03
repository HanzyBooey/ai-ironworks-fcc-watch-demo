# AI Ironworks — FCC Cellular License Watch (demo)

Paper demo for a **United States FCC cellular license-watch** style product desk: sample license rows + map-ready GeoJSON stubs.

## What an evaluator should see

- Clear product shape (watch licenses → alert / map)
- Sample data only — no live FCC scrape in this repo
- Stack notes pointing at real libraries we use elsewhere (`Leaflet`, `d3-geo`, `better-sqlite3`)

## Layout

| Path | Purpose |
| --- | --- |
| [`samples/licenses.json`](./samples/licenses.json) | Fake license rows |
| [`samples/coverage.geojson`](./samples/coverage.geojson) | Tiny GeoJSON stub |

## Related owned tools

- [vercel/next.js](https://github.com/vercel/next.js)
- [Leaflet/Leaflet](https://github.com/Leaflet/Leaflet)
- [WiseLibs/better-sqlite3](https://github.com/WiseLibs/better-sqlite3)

Product desk work lives under AI Ironworks ops; this public repo is a **portfolio sample**.

© AI Ironworks
