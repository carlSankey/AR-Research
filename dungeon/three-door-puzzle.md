# The Riddle of the Three Doors (Dungeon level 1)

Also called the Blink Mine rooms. This is the way to **Acrinimiril's tomb**.

## The cluebook version
- After you free **Ozob** from the Palace prison, he sends you to a corridor at **33N, 16E**, facing East with a door in front of you. Go through, then face North.
- Each room has three doors; each door is a blink mine (teleport).
- Wrong door → the **Reject Room** at **38N, 4E**.
- The last room has **four** doors, one of them invisible.
- The right sequence ends in a **Large Room at 32N, 20E**, near the tomb.
- Sequence: **middle, left, left, middle, middle**.

## Door by door (x,y – see docs/coordinates.md)
Each door is a square with a door on one side and a teleport on it. "Facing" is the direction you face after the teleport (from the original's facing byte: 0 N, 1 E, 3 W, FF = unchanged).

| Room | You face | Left | Middle | Right |
|---|---|---|---|---|
| 1 – from 17,30 | N | 17,29 → 18,30 (back) | **18,29 → 18,27, facing W** | 19,29 → Reject Room |
| 2 – 18,26–28 | W | **17,28 → 19,27, facing E** | 17,27 → Reject Room | 17,26 → 18,27 (same room) |
| 3 – 19,26–28 | E | **20,26 → 15,23, facing N** | 20,27 → 18,27 | 20,28 → Reject Room |
| 4 – 15,23 | N | 14,22 → 18,30 | **15,22 → 29,23, facing N** | 16,22 → Reject Room |
| 5 – 29,23 | N | 28,22 → Reject Room | **29,22 → 20,31 (Large Room), facing N** | 30,22 → 19,27 |

- The invisible fourth door in room 5 has not been found yet (**unverified**).
- The Reject Room teleport in the data lands at 5,26 (cluebook 38N,4E = 4,25).
- From the Large Room (20,31) a winding passage leads east to 29,27 → 30,27 → the tomb at 31,27, entered from the west.

Source: Dungeon cluebook (eobet.com); door squares and destinations from the converted level 1 map.
