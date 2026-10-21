# 05 Destination Authority

Authority requires a structured body of knowledge that becomes more useful with every article, listing and industry conversation. Guides written only from publicly available information do not build it.

## The destination hierarchy

| Level | Examples | What this level contributes |
|---|---|---|
| Region | Europe, Asia, Middle East, Oceania, Africa, North America | Comparison across countries, seasonality at a glance, how the region suits different celebrations |
| Country | Italy, Greece, Bali (Indonesia), Fiji | Legal and cultural context, seasonality, accessibility, travel considerations |
| Area | Lake Como, Amalfi Coast, Tuscany, Uluwatu | Local character, guest logistics, venue ecosystem, surrounding experiences |
| Venue or experience | A specific estate, hotel, island, planner | Verified details, defining qualities, suitability and access |

Each level adds a different kind of information. A region guide does not repeat country guides; a country guide does not merely list properties already profiled. Each level links up and down.

The structure in `knowledge/dossiers/` mirrors this hierarchy:

```
knowledge/dossiers/<region>/_region.md
knowledge/dossiers/<region>/<country>/_country.md
knowledge/dossiers/<region>/<country>/<area>.md
knowledge/listings/<slug>.md          (venue and supplier records)
```

## The editorial dossier

Template: `templates/destination-dossier.md`. Owner: `ww-research-intelligence`. Run with `/ww-dossier <destination>`.

Every dossier covers:
- **Seasonality:** weather, peak periods, shoulder seasons, climate limitations.
- **Wedding logistics:** legal ceremony requirements, symbolic alternatives, permits and restrictions.
- **Travel intelligence:** airports, transfers, travel times, connections, guest mobility.
- **Accommodation:** room capacity, nearby hotels, group stays, accommodation styles.
- **Venue ecosystem:** estates, villas, hotels, private islands, historic properties, specialist spaces, with classifications.
- **Local expertise:** planners, caterers, designers, photographers and other credible professionals.
- **Guest experience:** dining, culture, wellness, excursions, post-wedding travel.
- **Commercial and editorial records:** source links, last-verified dates, partnership disclosures, outstanding questions.

## Verification

Legal requirements, availability and travel arrangements are verified against current primary sources before publication. Each fact in a dossier carries a source and a verified date. Facts older than their review interval (see `templates/destination-dossier.md`) are re-verified before they are reused in a new asset.

## Why it compounds

A credible dossier lets the team produce a stronger landing page, a more useful listing, a seasonal guide, a honeymoon article and a social feature without starting research again. Before any destination asset is briefed, check the dossier first; after it is published, file what was learned back into the dossier.
