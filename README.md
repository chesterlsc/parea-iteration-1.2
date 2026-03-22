# parea-iteration-1.2

Current homepage build for Parea Collective.

Previous version:
[parea-iteration-1.1](https://github.com/chesterlsc/parea-iteration-1.1)

## What This Version Is

This version updates the existing Parea Collective site using the final website copy and brand kit as the source of truth, while preserving the site's premium minimalist direction, light-mode presentation, and overall one-page structure.

The build keeps Parea positioned as the operating layer behind modern business, with the ecosystem organized around:

- `systems`
- `marketing`
- `education`
- `ownership`

## What Changed From `parea-iteration-1.1`

Compared with `parea-iteration-1.1`, this build implements the following:

- Applied the updated brand kit across the site:
  - off-white base `#f6f5f3`
  - charcoal text `#2d2d2d`
  - green structural color `#47584e`
  - gold accent `#c1a875`
  - supporting neutral `#9fa6a0`
- Standardized typography so headers use `Montserrat Bold`, subheads use `Montserrat`, and body text uses `Inter`.
- Rewrote the hero section with the new eyebrow, headline, subhead, and CTA labels.
- Replaced the old ecosystem card copy with the final ecosystem structure for:
  - `Aegis & Co.`
  - `NAMI.`
  - `PCAA`
  - `Acquisitions`
- Updated the `systems & companies` section copy and changed the secondary view from `companies` to `ecosystem`.
- Replaced the section content inside the ecosystem view with the final descriptions for each entity.
- Removed the old founder section entirely and replaced it with a philosophy section.
- Rebuilt the philosophy section into a centered statement with a supporting paragraph and three evolving principle cards.
- Refined the philosophy cards so they read as a left-to-right progression, use a stronger headline-style font, and support horizontal scrolling on mobile.
- Updated the acquisitions section with the new ownership-first positioning and CTA.
- Cleaned up footer copy and removed outdated text from previous iterations.
- Polished capitalization and punctuation site-wide so the final copy is more consistent and presentation-ready.

## Philosophy Section Changes

The philosophy section changed the most from the earlier iteration.

What was implemented:

- The founder-led narrative was removed in favor of a systems-led philosophy statement.
- The philosophy heading now anchors the section as a clear brand point of view.
- The supporting paragraph was tightened to remove redundancy and improve readability.
- The three principle cards were redesigned as equal rectangular evolution cards that progress from simple to more resolved from left to right.
- The principle cards now use layered back-planes, a front-face content layer, desktop hover behavior, and mobile horizontal scrolling while staying visually aligned with the rest of the site.

## Current Site Structure

The current homepage order is:

1. Hero
2. Ecosystem
3. Systems & ecosystem
4. Philosophy
5. Acquisitions
6. Footer

## Implementation Notes

- The site remains a static single-page build.
- The existing visual direction was preserved rather than redesigned from scratch.
- Desktop and mobile layouts were both updated to stay polished after the new copy and philosophy changes.
- The site stays in light mode.

## Tech Notes

- Static site
- Main files: `index.html`, `styles.css`, `script.js`
- Assets folder: `assets/`
- Intended branch: `main`
