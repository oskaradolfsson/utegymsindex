# Utegymsindex 2026: utegym per 10 000 invånare i Sveriges 290 kommuner

Outdoor gyms (utegym) and lit exercise tracks (elljusspår) per 10,000 residents for every Swedish municipality, with rank.

- 92 of 290 municipalities have no outdoor gym mapped in OpenStreetMap.
- Övertorneå has the most per resident: 5 outdoor gyms for 3,995 residents, 12.52 per 10,000.

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
