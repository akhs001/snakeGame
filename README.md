# VOID SERPENT

A sci-fi, neon-drenched take on Snake. Open `index.html` in any modern browser — no build step, no dependencies.

## Features
- **Smooth, interpolated movement** with glowing cybernetic serpent, particle FX, screen shake and CRT styling
- **Two arenas:** force-field walls (deadly) or warp space (wrap-around)
- **Three pilot ranks:** Cadet / Pilot / Commander (speed + hazard density); separate high score for each arena/rank
- **Sectors:** every few cores you jump to a new sector with a new palette and more hazards
  - Sector 1: asteroids (always placed so the arena stays fully reachable)
  - Sector 2+: **wormhole** pairs that teleport you
  - Sector 3+: **laser gates** that cycle off → warning → fire
  - Sector 4+: patrolling **hunter drones**
- **Pick-ups:** energy cores, timed **quantum cells** (bonus), and power-ups: **Shield**, **Phase** (ghost mode), **Chrono** (slow time), **x2 Amp**, **EMP** (purges nearby hazards, jams lasers)
- **Combo multiplier** (up to x5) for eating cores in quick succession
- **Thruster boost** (hold Space/Shift): faster, and cores are worth x1.5, but it drains an energy meter
- Procedural sound effects + generative backing track (mute with `M`)
- Touch support: swipe to steer, on-screen boost button

## Controls
| Action | Keys |
|---|---|
| Steer | Arrow keys / WASD (or swipe) |
| Boost | Hold Space / Shift |
| Pause | P / Esc |
| Mute | M |
| Menu | ↑↓ row, ←→ change, Enter to launch |
