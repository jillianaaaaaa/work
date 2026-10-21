# 08 The Listing Standard

Listings are often treated as low-effort, repetitive content. In a destination-led publication they are a major expression of editorial judgement.

## Structure

Every listing follows the same information architecture with a distinctive description:

1. **Editorial positioning:** what the property or provider is, where it is, what distinguishes it.
2. **Defining features:** architecture, landscape, design, service philosophy, facilities or specialist capabilities.
3. **Wedding suitability:** ceremony and reception options, capacity, exclusivity, restrictions, event formats (verified only).
4. **Guest experience:** accommodation, dining, transport, surrounding attractions, multi-day possibilities.
5. **Practical details:** location, access, seasonality, contact, official links.
6. **Editorial classification:** Signature, Specialist or Emerging, and the celebration, traveller or requirement it particularly suits.

## Facts and copy are separate

Each listing is a single record (`knowledge/listings/<slug>.md`, from `templates/listing-record.md`) with:

- **Structured fact fields** in the front matter: location, capacities, exclusivity, seasons, rooms, contact, official links, each with a source and a verified date.
- **Editorial copy** in the body, written to the six-part structure.
- **Record fields:** last verified date, unconfirmed details, commercial relationship and disclosure requirement, classification and reason, related dossier.

Facts can then be updated without losing the writing, and the writing can evolve without compromising data accuracy.

## Approval test

A listing is approved only when it answers what makes the place distinctive, what celebration it accommodates, what its location contributes and why it merits our audience's attention (see `01-philosophy.md`). Run `/ww-listing <name>` to produce one.

## Listing health

Tracked monthly in the scorecard: verification freshness (share of listings verified within 12 months), completeness (required fields filled), broken links and update compliance.
