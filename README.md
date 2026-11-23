# Utegymsindex 2026: utegym per 10 000 invånare i Sveriges 290 kommuner

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24463909.svg)](https://doi.org/10.5281/zenodo.24463909)

Outdoor gym sites (utegym) and lit exercise tracks (elljusspår) per 10,000 residents for every Swedish municipality, with rank, as registered in OpenStreetMap.

**Read this first.** OpenStreetMap misses many outdoor gyms. In a spot check on 23 November 2026, 11 of 17 municipalities with 0 here had at least one outdoor gym on the municipality's own site or Naturkartan. Treat the figures as what is mapped, not what exists. A count checked against every municipality's own records is in progress.

Since v1.1.0, points that belong to the same place are merged into one site (stations along a trail, machines in one park): within 300 m, 600 m if one point has no name, 1,200 m for numbered stations. `osm_fitness_points` keeps the raw count.

Files:

- `data/utegymsindex-2026.csv` (UTF-8, comma separated)
- `data/utegymsindex-2026.json`

Columns: rank (shared rank for equal values), municipality code, municipality, county code, population, outdoor gyms, outdoor gyms per 10,000, lit tracks, lit tracks per 10,000, all mapped places, and the municipality's page on amblecoach.com.

Method, charts and the full ranking in Swedish: **https://amblecoach.com/sv/data/utegymsindex/**

## Sources and caveats

- Outdoor gyms and tracks: OpenStreetMap contributors, extract 2026-11-13 ([ODbL](https://opendatacommons.org/licenses/odbl/1-0/)). A gym that nobody has mapped is not counted. Anyone can add a missing gym to OpenStreetMap, and the index follows on the next extract.
- Population: Statistics Sweden (SCB), table TAB5557, 2025 (CC0).

The place-level data behind the counts is in [utegym-sverige](https://github.com/oskaradolfsson/utegym-sverige).

## Licence

[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/), because the counts are derived from OpenStreetMap. Credit: "Utegymsindex 2026, Amble (amblecoach.com), data © OpenStreetMap contributors".

Made by [Amble](https://amblecoach.com).

## Cite

Archived on Zenodo with a DOI: https://doi.org/10.5281/zenodo.24463909
