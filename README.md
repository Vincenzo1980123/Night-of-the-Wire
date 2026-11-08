# Night of the Wire

An isometric stealth-adventure in a single HTML file. It's night in a fictional prison camp run by "the Directorate". You play Aren, and you need to find three other prisoners, Mira, Tomas and Bram. Each of them, controlled by the game's AI, can do one thing you can't. Then all four of you have to get through the wire.

Open `index.html` in any modern browser. There's nothing to build or install.

## Controls
| Key | Action |
| --- | --- |
| WASD / Arrows | Move |
| 1 · 2 · 3 (Shift) | Normal · Sneak · Sprint |
| E / Space | Act: talk, take, open, knock out a guard from behind |
| Q | Tell your whole group to wait or follow |
| P / Esc | Pause |

On touch devices you get an on-screen stick plus ACT, MODE and GROUP buttons.

## How it plays
- **Companions:** they follow you and copy your stance, so they crouch when you sneak. They warn you when a guard is looking their way. Guards can catch them, and then they're locked in the cells next to the guard office until you let them out.
- **Guards:** each one patrols with a vision cone that walls block. Suspicion builds up before they start chasing you. When a chase is lost they search the area, and then they go back to their route. Sprinting makes noise that guards can hear.
- **Light:** lamps and searchlights let guards see you from much further away. Once Tomas has killed the generator, the whole camp goes dark and the outer fence is no longer electrified.
- **Objectives:** Bram clears the workshop door so you can get the wire cutters. Mira picks the lock on the guard office so you can take the keycard. Tomas cuts the power. Then you open the inner gate, cut through the fence and get into the forest.
