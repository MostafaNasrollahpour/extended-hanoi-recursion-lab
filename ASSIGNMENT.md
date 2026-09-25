# Assignment: Extended Towers of Hanoi

The goal of this exercise is to practice recursive problem solving. The visualization and disk movement system are already implemented; complete the recursive algorithms in `Project Structure/script.js`.

Before coding, write pseudocode for each problem and identify its base case and recursive subproblems.

A move from rod `A` to rod `B` is recorded as:

```js
moves.push([A, B]);
```

## 0. Classic Hanoi

Implement the standard Towers of Hanoi algorithm. Move `n` disks from `from` to `to` using `via`, while preserving the classic rule that a larger disk may never be placed on a smaller disk.

## 1. Extended Hanoi 1

This problem uses three rods. For each level, one disk starts on the first rod, two on the second rod, and three on the third rod. The pattern continues until the first rod contains `n` disks.

Move all disks to the third rod while preserving the classic Hanoi rules.

## 2. Extended Hanoi 2

This problem uses four rods. Given `n`, `n` white disks start on the first rod and `n` gray disks start on the third rod.

Swap the two groups. Disks of opposite colors may not be placed on top of one another.

## 3. Extended Hanoi 3

This problem uses three rods. For each level, one disk starts on the first rod and two disks start on the second rod. The pattern continues until the second rod contains `2n` disks.

Move all disks to the third rod while preserving the classic Hanoi rules.

## 4. Extended Hanoi 4

This problem uses four rods. `n` disks start on the first rod and must be moved to the third rod.

In addition to the classic Hanoi rules, moves are allowed only between:

- `A ↔ C`
- `A ↔ D`
- `B ↔ C`
- `B ↔ D`

Direct moves between `A ↔ B` and `C ↔ D` are not allowed.

## 5. Extended Hanoi 5

This problem uses four rods and the same `1 / 2 / 3` initial distribution pattern as Extended Hanoi 1.

In addition to the classic Hanoi rules, disks may move only between adjacent rods, with `A` and `D` also considered adjacent:

- `A ↔ B`
- `B ↔ C`
- `C ↔ D`
- `D ↔ A`

## Playback controls

| Key | Action |
| --- | --- |
| `A` | Previous move |
| `S` | Start playback |
| `D` | Next move |
| `Space` | Stop playback |
