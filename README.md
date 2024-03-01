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
- Risk of panning getting stuck. TEST

### Selection & Selectables
- Selection object
- Selectable component
- Pulsating selected indication decal

#### Issues
- Shift & Ctrl is not registered. CHANGED

### Player Controller
- Input handling for Top-down camera
- Input handling for Selectables

#### Issues
- Mouse capture doesn't work.

### Build 1
- Tested & uploadet to Itch.



## Day 2: Friday
I fixed/reworked most of the issues from yesterday and updated the selection interface.
Also experimented with Behaviour Trees but found them combersome for simple actions. The character AI will be so basic, there's no need for a BT, probably.

### Selection
- Selection is now: click to select, drag to multi-select.
- Selection Category is used to limit which types of actors can be combined in a selection.

### AI Controller
- Simple navigate to function.

#### Issues
- Missing Assignment
- Missing Combat
- Missing flock control

### Build 2
- Uploadet to Itch & Tested.

