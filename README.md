# Pit Lane Escape

A Formula 1 themed sliding-block puzzle. Your race car is boxed in on pit lane by support vehicles and rival cars. Slide them out of the way and get your car to the pit exit in as few moves as you can.

**Play it:** https://davebamf-dot.github.io/pit-lane-escape/

## How to play

- Drag a vehicle along its lane. Cars and trucks only move forwards and backwards, never sideways.
- You can also select a vehicle with Tab and move it with the arrow keys.
- Tyre barriers never move.
- The pit exit can be on any side of the grid. Your car always faces it, and its lane is painted red.
- The clock starts when the five start lights go out. If you move before then, it's a jump start.

## Sessions

The session you pick sets the difficulty: how many moves the best solution takes (par).

| Session | 5×5 | 6×6 and 7×7 |
|---|---|---|
| Practice | 3–5 | 4–7 |
| Qualifying | 6–9 | 8–13 |
| Sprint Race | 10–13 | 14–20 |
| Grand Prix | 14+ | 21+ |

Every lap is a new puzzle, built in your browser and checked by a solver, so there's no end to the levels.

## Timing sheet

- **Finishing position:** P1 means you matched par. Each extra move drops you a place.
- **Points:** Sprint Races and Grands Prix score F1-style points, plus a bonus point for a fastest lap.
- **Lap times, averages and streaks:** tracked for each session and grid.
- **Sectors:** purple marks a new personal best.
- **Laps led:** laps you won at P1 with no pit stops.
- **Pit stops:** hints.

Stats are saved in your browser's local storage.

## Built with

One HTML file with no build step and no dependencies apart from two Google Fonts. Open `index.html` in a browser to play offline.
