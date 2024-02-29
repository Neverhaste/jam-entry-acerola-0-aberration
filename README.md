# Game Jam entry for Acerola Jam 0 'Aberration'
My entry for Acerola Jam 0 with the theme 'Aberration'.

### Links:
~~- [Playable in browser (Chrome)](https://neverhaste.itch.io/aberration)~~
- [Neverhaste at Itch.io](https://neverhaste.itch.io/)

- [Acerola Jam 0 at Itch.io](https://itch.io/jam/acerola-jam-0)

# Dev Log
I will try to keep a daily dev log, but I am also 100% sure that I will miss atleast a few days.

## Day 1: Thursday
I have decided to make a colony-management style game with a simulated environment where Abbarations (mutations) occur, spread and mix, threatening the colony.

### Top-down Camera
- Clamped pan with interpolation
- Follow target
- Clamped distance with interpolation
- Clamped orbit (Y,Z) with interpolation

#### Issues
- Missing terrain-following capability.
- Risk of panning getting stuck.

### Selection & Selectables
- Selection object
- Selectable component
- Pulsating selected indication decal

#### Issues
- Shift & Ctrl is not registered.

### Player Controller
- Input handling for Top-down camera
- Input handling for Selectables

#### Issues
- Mouse capture doesn't work.

### Build 1
- Tested & uploadet to Itch.
