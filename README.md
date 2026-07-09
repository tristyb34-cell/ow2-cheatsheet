# Overwatch 2 Cheat Sheet

Live: https://tristyb34-cell.github.io/ow2-cheatsheet/

A single self-contained HTML page. No build step, no dependencies, no server.
Open `index.html` in any browser.

## What's in it

- **Stats** for all 52 heroes: real win and pick rates, selectable by competitive division
  (Bronze through Grandmaster, plus all-ranks).
- **Counter Picker**: choose an enemy hero, get ranked answers. Heroes confirmed by both
  directions of the counter graph are marked *strong*. Your starred heroes sort first.
- **Heroes**: per-hero synergies, counters, tips and provenance.
- **Abilities & Perks**: every hero's live kit, including all four perks (two minor, two major).
- **Compositions, When to Swap, Ult Combos, Map Tips**: carried over from the March 2026 version
  of this file and not re-verified against the current patch. Each is labelled as such in the page.
- **Survival Guide**: four things that keep each hero alive.

Star heroes to build a personal pool. It persists in `localStorage`.

## Where the data comes from

| Data | Source | Nature |
|---|---|---|
| Roster, roles, subroles, HP, abilities, perks | Blizzard hero data via the OverFast API | Factual |
| Win rate, pick rate | Blizzard official hero statistics (PC / Americas / competitive) | Factual |
| Counters, synergies, tips for 10 newest heroes | Researched and cited per hero, sources linked on each card | Sourced opinion |
| Counters, synergies, tips for the other 42 heroes | Hand-written, March 2026 | Unverified opinion |

Latest patch reflected: **2 July 2026**. Data pulled **9 July 2026**.

There are deliberately **no S/A/B/C tier letters**. Blizzard publishes win rates, not tiers, and
converting one into the other is a formula dressed up as a fact. Cards where the strategy text
was researched carry a confidence badge and a list of caveats; cards carried over from March say so.

Where no reliable data exists, the page says "No reliable data" rather than inventing a matchup.
Wuyang's "Strong into" list is empty for exactly this reason.

## Attribution

Hero portraits are the property of Blizzard Entertainment and are embedded here for
non-commercial, personal reference. Overwatch is a trademark of Blizzard Entertainment, Inc.
This is an unofficial fan-made reference and is not affiliated with or endorsed by Blizzard.

Every `<img>` degrades gracefully: if the images are removed, the page still reads as text.
