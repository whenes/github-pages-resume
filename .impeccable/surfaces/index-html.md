---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

## Scope

`index.html`: the public portfolio at the GitHub Pages root, assembled from the dev components (tokens.css, base.css, components.css, components.js) plus one new component, the horizontal career timeline. Mode: Experience; the career itself leads the first viewport.

## Audience and job

Recruiters and hiring tech leads skimming for two minutes; they must grasp 10+ years, the consulting branch with client placements, the modernization record, and reach email/LinkedIn/GitHub. Content only from the resume PDF and public GitHub.

## Constraints

Static, no build. Vertical `.gitlog` is the canonical no-JS and mobile content; the horizontal timeline is a progressive enhancement built from its data attributes. Resume buttons stay aria-disabled until the PDF exists. No phone number.

## Direction contract

THESIS: the career is a navigable git graph across time, overlaps and the consulting branch visible at a glance; refuses the stacked job-card résumé and the hero-plus-grid portfolio.
OWN-WORLD: DESIGN.md Steply night console: charcoal layers, blurple only for the consulting branch, selection and primary action, Inter UI, Unbounded for name, section titles and selected company, JetBrains Mono for years, dates, durations and refs.
STORY: who Whenes is; how 2010 lab work leads to a 2020 consulting branch with four client placements; what modernizing without stopping meant (flag case); proof in repos and skills; then contact.
FIRST VIEWPORT: topbar with section links and theme; full-width profile (name ~48px, role, location, current position, one summary line, actions); below it the full-width horizontal graph, 2010 to now, TOTVS selected, top of its detail panel visible.
FORM: dealt structure 7 (timeline), user-locked over the roll's lead; seed key 60ce84ab; signature interaction: lanes draw in on load, selecting a job re-renders the detail panel, arrow keys walk commits, hash deep-links a job.
FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance
