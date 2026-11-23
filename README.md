# Utegymsindex 2026: utegym per 10 000 invånare i Sveriges 290 kommuner

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24463909.svg)](https://doi.org/10.5281/zenodo.24463909)

Outdoor gyms (utegym) and lit exercise tracks (elljusspår) per 10,000 residents for every Swedish municipality, with rank. Checked on 23 November 2026.

How each municipality's count is made:

- **Official list** (43 municipalities, `confidence: high`): the municipality's own list of outdoor gyms.
- Otherwise the **highest of** Naturkartan, OpenStreetMap (points that belong to one place merged into one site) and named outdoor gyms found on municipal, tourism or news pages. These are marked `at_least: yes`, because no source is complete. `confidence: medium` = two sources agree or Naturkartan, `low` = one source.
- `none`: nothing found in any source. That is not proof that the municipality has no outdoor gym.

The `sources` column lists the pages used. Corrections are welcome: open an issue.

Files:

- `data/utegymsindex-2026.csv` (UTF-8, comma separated)
- `data/utegymsindex-2026.json`

Columns: rank (shared rank for equal values), municipality code, municipality, county code, population, outdoor gyms, at_least, confidence, basis, outdoor gyms per 10,000, OpenStreetMap sites, raw OpenStreetMap points, lit tracks, lit tracks per 10,000, sources, and the municipality's page on amblecoach.com.

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
