# Coordinates

## Original games (manuals, cluebook)
Written as **North, East** – e.g. "33N, 16E". On the 64×64 maps (City, Dungeon level 1) North counts up from the **south** edge.

## x,y in this repository
`x` counts east from the west edge, `y` counts **south from the north edge** (y = 0 is the north row).

    x = E
    y = 63 − N      (64×64 maps)

Checked against the cluebook: Ozob drops you at 33N,16E = 16,30; the Large Room is 32N,20E = 20,31; the Reject Room is 38N,4E = 4,25.

The `orig_N` / `orig_E` columns in `maps/` are only filled in for the 64×64 maps. Levels 2–4 are smaller and their original numbering has not been checked (**unverified**).

## Walls and doors
In ARX's maps (and the original), a door can belong to one side of a square only – so some doors are one-way. Keep that in mind when checking whether an area can be reached.
