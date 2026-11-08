# Night of the Wire

An isometric stealth adventure in a single HTML file, playable on desktop and on phones (iPhone included). It's set in Grauhof, a fictional camp run by "the Directorate". By day you do forced labour that helps the people who keep you there. By night you try to get yourself and three friends, Mira, Tomas and Bram, through the wire.

Open `index.html` in a browser. There's nothing to build or install.

`prototype.html` is a standalone art-direction prototype: a yard, a barrack you can walk into, and a character turntable. It's for approving the next visual pass before it goes into the game.

> Content note: the game depicts a fictional extermination camp, forced labour and the line of people walked into the East Block. Nothing graphic is shown, but it is meant to be heavy.

## A day in Grauhof
- **Roll call (06:00):** choose today's work. Every job helps the oppressor. Some give you something; the heaviest gives you the most.
  | Job | Weight | What you gain |
  | --- | --- | --- |
  | Laundry | +2 | Nothing |
  | Kitchen yard | +6 | Two scraps of meat to keep a guard dog busy |
  | Workshop | +10 | The wire cutters |
  | Guard office | +18 | The spare gate keycard |
  | **Special detail: the East Block** | **+35** | Tonight guards let you through and you may enter the East compound; the dogs learn your scent for good; you learn the breaker that kills the camp lights |
- **Day:** go to your job and hold Act to work. There are no searchlights, but there's nowhere to hide either. If you wander off, guards order you back, and after five seconds they beat you back to your post.
- **Night (22:00–05:30):** searchlights, lamps, guards and dogs. This is when the escape can happen. You must be back in a barrack by dawn roll call, or it counts as a failed attempt. You can also sleep through the night on your bunk.
- **Weight:** what the work does to you. High Weight shortens your breath, slows your hands and brings intrusive thoughts. Talking to people in the barracks at night eases it.

## How it ends
- **Escape:** cut the power, open the inner gate, cut the outer fence, and reach the forest with whoever is still with you.
- **Caught:** the first two times you're thrown back in your barrack. The third time, you are put in the line to the East Block. You can't leave the line, and the ending can't be avoided.
- **Selection:** after the fifth night, Block A is selected. If you've only worked and never escaped, you end up in the line anyway. Five full days played without skipping take about 30 minutes; finishing work early or sleeping through a night makes the time pass faster.
- **Friends:** friends still in the cells at dawn are taken east and are gone for good.

## Visual style
The look is mid-1990s European isometric 3D adventure games: polygonal characters walking through a hand-painted miniature world. All designs are original.
- **Characters:** real-time low-poly 3D figures with flat, faceted shading from a single light direction. They have toy-like proportions: oval heads, prominent noses, large simple eyes, oversized hands and boots. Their posture shows their state: prisoners stoop, the people in the line walk with their heads bowed, and guards stand upright. Poses blend smoothly between standing, walking, running, sneaking, sitting, kneeling to scrub and lying down.
- **Environment:** procedurally generated low-resolution textures (concrete block, weathered planks, tar paper, corrugated iron, terracotta, brick, dirt, gravel), thick walls with crisp edges, painted windows and doors, cast shadows and contact shadows at the base of walls.
- **Roofs:** they lift away when you step inside a building, so you see the interior in cutaway. Anything standing between the camera and you turns see-through.
- **Performance:** the static art for each tile is rendered once into cached sprites, the way old isometric engines pre-rendered their bricks. Only animated details are drawn live: wire shimmer, smoke, steam and the generator light.

## Controls
| Key | Touch | Action |
| --- | --- | --- |
| WASD / Arrows | Thumb stick | Move (tilt the stick gently to creep) |
| 1 · 2 · 3, Shift | WALK / SNEAK / SPRINT | Change stance |
| E / Space (hold to work) | ACT | Talk, take, open, throw a scrap, knock out a guard from behind |
| Q | GROUP | Tell your friends to wait or follow |
| P / Esc, M | II | Pause, sound on/off |

## Sound and text
- **Silent camp:** there is no gibberish "speech" and there are no game beeps.
- **Speech sounds:** a soft breath when someone whispers to you, and a muffled thud when a guard shouts.
- **Danger sounds:** a distant bark from the dogs, a quiet heartbeat while you're being hunted, and a slow, far-off siren during the random night alarms.
- **Action sounds:** soft physical noises, such as a click, a snip, a thud and the generator winding down.
- **Subtitles:** speech appears as film-style subtitles at the bottom, at most two lines at once, and only from people within earshot. Above a character's head there's only a small marker showing who is talking: dots for whispers, a red mark for shouts.
- **Action prompt:** sits just above the subtitles, with a faint ring on the floor under whatever it refers to.
