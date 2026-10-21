---
description: Run the Wedded Wonderland article pipeline through Checkpoint 1 (or continue an existing asset)
argument-hint: <topic, or content/<slug> to continue>
---
Run the editorial pipeline for: $ARGUMENTS

Invoke the `wedded-wonderland-articles` skill first. It governs article mechanics; `CLAUDE.md` and `editorial/` govern stages and judgement.

If the asset already exists in `content/`, read its `status.md` and continue from the current stage. Otherwise:

1. **Plan:** as `/ww-plan`. Stop if the editorial director recommends decline, and tell Jillian why.
2. **Research:** `ww-research-intelligence` writes `research.md`, starting from any existing dossier or listing and filing new knowledge back into `knowledge/`.
3. **Brief:** `ww-seo-strategist` supplies the keyword map, competitor patterns, gaps and link plan; `ww-writer` writes `brief.md` and the Checkpoint 1 outline exactly as the skill specifies (including 2 best-bet photos per slot from `ww-publishing-ops` sourcing rules). `ww-editorial-director` checks the angle against the three questions.
4. **Stop at Checkpoint 1.** Present the outline to Jillian. Do not draft until she approves.

After approval (when re-run on the asset):

5. **Produce:** `ww-writer` writes `draft.md` against the approved outline and runs the pre-delivery checklist.
6. **Review:** `ww-editorial-director` writes `review.md` at the tier's depth; for Tier 1 also get an SEO review from `ww-seo-strategist` and a fact trace from `ww-research-intelligence`. `ww-writer` applies changes. Deliver to Jillian as Checkpoint 2.
7. **Publish:** after Jillian approves, `ww-publishing-ops` writes `publish.md`.
8. **Learn:** `ww-seo-strategist` logs it in `knowledge/performance-log.md` with a refresh date.

Update `status.md` (stage, owner, change log) and `content/PIPELINE.md` at every stage.
