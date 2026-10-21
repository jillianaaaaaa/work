# SEO Review: How to Choose a Wedding Weekend Venue That Hosts Every Occasion

**Stage:** 05 Review (targeted SEO, Tier 2) · **Reviewer:** ww-seo-strategist · **Date:** 21 October 2026 · **Reviewed:** `draft.md` (not edited), against `seo.md`, `outline.md` and the `wedded-wonderland-articles` skill

**Verdict: passes SEO review.** Two recommended refinements, no blocking changes. All counts below are from a scripted check of `draft.md` on 21 October 2026, not tool data.

## 1. Keyword density ruling

**Count confirmed.** "wedding weekend venue(s)" appears 14 times between the H1 and the end of the FAQ (lines 17, 19, 41, 55, 135, 137, 151, 163, 165, 175, 187, 229, 232, 238). My word count is 3,236 against the writer's 3,239; the difference is tokenising and does not change the result.

**Ruling: the house "1 to 2 percent" uses phrase-word share**, (occurrences x words in the phrase) / total words x 100. This draft: 14 x 3 / 3,236 = **1.3 percent. Inside the band. No additions needed.**

Reasoning:
- **Industry convention is split.** The classic keyword-density formula has a phrase variant that multiplies occurrences by the number of words in the phrase, which is the measure designed for multi-word keyphrases. Common CMS plugins (Yoast, Rank Math) instead report a raw occurrence rate. Neither is a Google ranking factor; Google does not publish a target density.
- **Only phrase-word share is compatible with the rest of the house standard.** On the occurrence measure, 1 to 2 percent of 3,236 words means 32 to 65 uses of a three-word phrase, roughly one every 50 to 100 words. That breaches the skill's own "never forced at the cost of grammar or flow" and `editorial/09`'s "Let keyword placement override voice or accuracy" prohibition. A rule cannot be read in a way that makes it contradict its own qualifier.
- **For single-word keywords the two measures are identical**, so the ruling changes nothing for those articles.
- **Plugin note for ww-publishing-ops:** a CMS plugin counting occurrences will show about 0.4 percent and may flag it as low. Ignore that flag when the phrase-word share is in band.

Ruling recorded as a one-line note in `editorial/09-seo-ai-discoverability.md`.

## 2. Opening, headings and AI Overview instructions

- **Wedded Wonderland in the first 100 words:** pass (deck, line 19, about word 30). The primary keyword is also in the deck.
- **H2s reuse the H1 pattern:** pass. Six of nine H2s carry "Wedding Weekend Venue" or "Venue for a Wedding Weekend"; H2 3 carries the secondary "Multi-Day Wedding" and the closing H2 carries "Destination Wedding Venue". "Itinerary" appears in no heading (cannibalisation guard with the live itinerary article holds).
- **Answer-first sentences:** pass under every H2 (lines 41, 57, 84, 137, 153, 165, 177, 189, 203). Each opens with a direct, self-contained answer. The H2 1 opener is the longest (37 words) and is the overall answer Google is most likely to lift, so tightening is recommended (R1).
- **The seven seo.md instructions for ww-writer (1 to 7):** all applied.
  1. H2 4 opener: verbatim (line 137); "wedding venues with accommodation" moved to the second sentence. Pass.
  2. FAQ 1 opener: verbatim (line 221), worded differently from H2 4. Pass.
  3. H2 3 opener: welcome party, wedding day and farewell brunch named in copy only (line 84). The writer removed my "from ... to" range; the reword keeps the AIO's three-occasion frame. Accepted.
  4. H2 5 opener: transfer point explicit, "on foot" correction accepted (line 153). Pass.
  5. Breathing-room sentence: line 86, venue lens only, no schedule. Pass.
  6. Guest count and nights named in H2 1 (line 41). Pass.
  7. FAQ 7 added, answer first, points to the minimum stay and the schedule guide, no pricing (line 239). Pass.
  - Instruction 10 asked for the schedule companion once, while instruction 7 asked for it in FAQ 7 as well. That conflict was mine. Two links with different anchors, far apart, is within the skill limit. Accepted.

## 3. Internal links

**34 internal links to 28 URLs** (confirms the writer's count). None on the never-link list: no business pages, no redirects, no Google-hidden pages (`/destinations/africa` correctly avoided).

| Linked twice | Lines | Anchors | Consecutive? |
|---|---|---|---|
| /a-wedding-weekend-itinerary-for-guest-experience (article) | 53, 239 | "wedding weekend schedule guide" / "how the days of a wedding weekend fit together" | No |
| /expert-advice/wedding-day-timeline (article) | 84, 177 | "wedding day timeline" / "wedding day timeline planner" | No |
| /plan-your-destination-wedding (service) | 43, 207 | "planning hub" / "destination wedding planning hub" | No |
| /destination-wedding-packages (service) | 139, 205 | identical anchors | No |
| /wonderland-concierge (service) | 153, 205 | "Wedded Concierge" both times (brand name, acceptable) | No |
| /wonderland-studio (service) | 177, 236 | "Wonderland Studio" both times (brand name, acceptable) | No |

Every other URL is linked once. No article exceeds two links and no pair sits in consecutive paragraphs. Article anchors are varied. The `/expert-advice/wedding-day-timeline` anchors are close variants; acceptable. The one keyword anchor that repeats exactly is "destination wedding packages", which R2 varies.

## 4. Meta and structured data

- **Meta title:** "Wedding Weekend Venues: How to Choose One That Hosts It All", 59 characters (max 60). Pass. Primary keyword leads.
- **Meta description:** 153 characters (max 160), Wedded Wonderland mentioned, primary keyword included. Pass.
- **Structured data (flag for ww-publishing-ops):** Article (headline, author, datePublished, dateModified, image), FAQPage (seven questions), BreadcrumbList. Agree: no ItemList (the properties are evidence, not a ranked list) and no HowTo. Expect no FAQ rich result (Google limits it to a narrow set of sites); the markup still aids machine reading.
- **Ops flag:** the disclosure line (line 241) sits directly after FAQ 7 under the FAQ heading. Keep it outside the CMS FAQ block so it is not marked up as part of the FAQ 7 answer in FAQPage. FAQPage answer text must match the visible answers exactly.
- **Ops flag:** set dateModified at every fact refresh. The page's citation case rests on dated operator figures.

## Recommended changes (non-blocking, writer's call with ED)

**R1. Line 41, tighten the quotable answer for AI Overviews.**
> "Choose a wedding weekend venue by testing whether one property can host every occasion and every guest across the stay, including the welcome dinner, the ceremony, the celebration and the lunch the day after. Bring two figures to every venue conversation, your guest count and the number of nights, because each test that follows turns on them."

Replace with:
> "Choose a wedding weekend venue by testing whether one property can host every occasion and every guest across the stay. That means the welcome dinner, the ceremony, the celebration and the lunch the day after. Bring two figures to every venue conversation, your guest count and the number of nights, because each test that follows turns on them."

(Still three sentences; keyword count unchanged.)

**R2. Line 205, vary the repeated anchor.**
> "Our [destination wedding packages](https://weddedwonderland.com/destination-wedding-packages) bring the venue, a group room block, guest transfers and an on-the-ground planner together at the resorts they cover."

Replace with:
> "Our [packaged destination weddings](https://weddedwonderland.com/destination-wedding-packages) bring the venue, a group room block, guest transfers and an on-the-ground planner together at the resorts they cover."

## Stage 07 handover

At publish, log in `knowledge/performance-log.md`: target query "wedding weekend venues", Tier 2, refresh 2 to 16 December 2026 (6 to 8 weeks). Still outstanding from Jillian: AI Overview screenshots for "wedding weekend venues", "wedding venues with accommodation" and "exclusive use wedding venue".
