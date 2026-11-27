# Alternate Reality – shared research and data

Facts about the **original** *Alternate Reality: The City* and *The Dungeon* (Paradise Programming / Datasoft, 1985–87), gathered while working on remakes. Shared so the different Alternate Reality projects don't each have to reverse-engineer the same things.

**In scope:** maps and special squares, items, puzzle solutions, quest chains, how the original's systems work, and where each fact comes from.
**Out of scope:** new content invented by any remake, original disk images, and large extracts of the disassemblies – link to those instead.

## Contents
| Path | What |
|---|---|
| `maps/` | Special squares per map (City, Dungeon levels 1–4) as CSV – treasures, venues, teleports, fixed encounters, messages |
| `docs/coordinates.md` | Original N/E coordinates vs x,y |
| `dungeon/staff-of-acrinimiril.md` | The staff quest: Ozob, King Danjor, the Great Dragon, the tomb, the PAC Card |
| `dungeon/three-door-puzzle.md` | The Riddle of the Three Doors – door-by-door solution with coordinates |
| `dungeon/endgame.md` | Clothes Horse → Mirrored Shield → Death's Door → Alien Control Room |
| `docs/sources.md` | Where the facts come from |

## Status of the data
- The `maps/` CSVs were exported from ARX's converted maps (27 Nov 2026). The squares come from the original games, but the `type`/`p1…p5` columns use ARX's file format and numbering (e.g. venue numbers, items.csv rows), so use `text`, `item_name` and `location_text` to match them to your own data.
- A few Dungeon level 4 squares were changed in ARX (the lift room moved to 7,2; a door added at 1,2) – see `dungeon/endgame.md`.
- Anything marked **unverified** has not been checked against the original game yet. Corrections are very welcome.

## Contributing
Open an issue or pull request. Please give a source for each fact (disassembly file, cluebook page, manual, a play-through, a screenshot).

## Licence
Text and data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) – use it in any project, just credit this repository. *Alternate Reality* itself belongs to its rights holders; this repository only describes it.

Maintained by Carl Sankey (ARX).
