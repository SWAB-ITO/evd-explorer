# SWAB Event Day Explorer (published pages)

Built pages only, served by GitHub Pages. One folder per event year.
The source (build, views, tests) lives in the private repo `Shop-with-a-Bulldawg-SWAB/EVD`
under `tools/event-explorer/`. Pages are built there from that year's exported CSVs,
checked with `build/pii-scan.js` (must print `PII HITS: 0`), and copied here.
A published year is not rebuilt unless something on it is wrong.
