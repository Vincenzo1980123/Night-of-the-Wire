# Night of the Wire

An isometric stealth adventure in a single HTML file, playable on desktop and on phones (iPhone included). It's set in **Greywater**, a fictional present-day facility run by a fictional regime, **the Directorate**. People it has labelled undesirable are held there, worked, and eventually taken to the East Block, from which nobody returns. By day you do forced labour that helps the people who keep you there. Whenever you can, you try to get yourself and three friends, Mira, Tomas and Bram, out.

**Play it online:** https://vincenzo1980123.github.io/Night-of-the-Wire/ (works on phones too; the real recordings load there).

Or open `index.html` in a browser. There's nothing to build or install. (Served over http, the game also loads the recordings in `audio/`; opened as a local file, it uses its synthesised fallbacks.)

`prototype.html` is the standalone art-direction prototype (a yard, a barrack you can walk into, a character turntable) that the game's look was approved from.

> Content note: the game depicts a fictional detention and extermination facility, forced labour, violence by guards, and people walked into the East Block. Nothing graphic is shown, but it is meant to be heavy. The setting is invented and modern; it deliberately avoids references to any real historical camp or regime.

## The facility
- **North:** the main gate in the outer fence, the strip in front of it, the workshop, the power house and the guard office.
- **Middle:** Blocks A, B and C, the kitchen yard, the cells, and the guarded passage into the East compound.
- **South section:** the canteen, the infirmary, the water basin with its wash troughs, Blocks D and E, and the guardhouse with its rifle rack.
- **East compound:** the East Block, with a steel vent stack that hums all night, and a burn pit beside it. A long fenced corridor runs down to the arrivals gate in the south fence. This is the only fenced-off area inside the facility.
- **Outside the south fence:** a railway ramp, a small station, two tracks and a standing freight train of shipping containers behind a diesel locomotive. At night a horn announces another line, which walks from the ramp through the arrivals gate to the East Block.
- **The Director:** the regime's (invented) leader, a heavy, bald, scowling man. A towering bronze statue of him in a greatcoat stands on a granite plinth in the middle of the yard.
- **Propaganda:** Directorate posters on outside walls and banners on most lamp posts. Half of them carry the Director's scowling portrait ("THE DIRECTOR IS WATCHING", "OBEY THE DIRECTOR", "HE KNOWS YOUR NUMBER"); the rest the regime's eye-in-a-hexagon emblem in teal and white, with slogans such as "ORDER · UNITY · OBEDIENCE", "THE DIRECTORATE SEES YOU", "COMPLIANCE KEEPS YOU SAFE" and "REPORT DISLOYALTY".
- **People:** prisoners wear bright orange jumpsuits. New arrivals in the line still wear their own everyday clothes. Guards wear dark tactical uniforms, helmets and a teal Directorate patch, and carry modern rifles.

## A day in Greywater
A working day lasts about 8 minutes (06:00 to 18:00). Nights last 3½ minutes.

- **Roll call (06:00):** choose today's work, or slip away. The jobs are spread across the facility: the workshop and the guard office in the north, the canteen, the infirmary and the laundry at the water basin in the south, and the East Block detail in the east. Every job helps the oppressor. Some give you something; the heaviest gives you the most.

  | Job | Weight | What you gain |
  | --- | --- | --- |
  | Laundry | +2 | Nothing |
  | Canteen | +6 | Two scraps of meat to keep a guard dog busy |
  | Infirmary | +8 | Ether: your next knockout lasts until morning |
  | Workshop | +10 | The wire cutters |
  | Guard office | +18 | The gate keycard |
  | **Special detail: the East Block** | **+35** | A special-detail pass for the night; the dogs learn your scent; you learn the breaker that kills the lights |

- **Bow to the Director:** once every day, go to the statue in the yard and press Act to bow (+1 Weight). Skip it and the guards beat you at the evening count (−15 health, +4 Weight). Guards let you walk to the statue during work, and other prisoners bow as they pass it.
- **Day:** go to your job and hold Act to work. If you wander off, guards order you back, and after five seconds they beat you back to your post.
- **Night (22:00–05:30):** searchlights, lamps, guards and dogs. Be back in a barrack by dawn roll call, or it counts as a failed attempt. You can sleep through the night on your bunk.
- **Weight:** what the work does to you. High Weight shortens your breath, slows your hands and brings intrusive thoughts. Talking to people in the barracks at night eases it.
- **Health:** drops when guards beat you (−15), when you're caught (−25) and when you're shot (−45).
  - A hit wounds you; it only counts as being caught when your health runs out.
  - Below 35 you're slower and short of breath, and the screen edges go red.
  - You heal slowly over time, faster resting in a barrack at night. Dr. Lamm in the infirmary treats you once a day (+35).

## Ways out
There's no fixed order and no required route.
- **Through the wire:** kill the power, then cut or climb the dead outer fence: **north** of the camp, or **south by the railway**.
  - The power house is padlocked. The key hangs on the key board in the guardhouse, at the far south end of the camp.
  - A guard, Calder, is posted at the power-house door. Knock him out from behind at night: he sweeps his gaze, so time it.
  - Inside, Tomas kills the generator *and* the backup: dark until morning. Pulling the breaker yourself (the East detail shows you which) only buys about **70 seconds** before the backup generator restarts the lights and the fence current.
  - Either way the two nearest guards come to check on the power house.
  - South of the fence, slip past the ramp guard, behind the train and across the tracks into the forest.
  - You need the wire cutters, or a blanket thrown over the barbs. There are only two blankets, on the linen shelf in the infirmary at the far south. Climbing over a blanket is slow (6 seconds) and noisy: guards nearby hear it.
- **Through the main gate:** the gate keycard (guard office job, or Mira at night) opens the main gate in the north fence, but only while the power is on: its lock is electric.
  - The card only works until dawn: the codes change every morning, so use it the night you get it.
  - A guard, Voss, is posted at the gate under a floodlight. He has to be knocked out (from behind, along the fence) or shot before you can use the reader.
  - The reader and the gate motor take 3½ seconds and are loud: patrolling guards nearby come to look.
- **Under it:** dig a tunnel under the bunks in Block A, on a skipped day or at night. Each morning's inspection may find it and fill it in.
- **Work is optional.** At roll call you can *slip away*. The barracks stay safe, but guards who spot you idle in the yard beat you back inside, and the evening count costs +6 Weight.
- **In daylight:** every action works by day too, but killing the power in daylight sets off the siren at once.
- **Friends are optional.** Recruit Mira, Tomas and Bram and bring them, or go alone. The ending reflects who made it, how and when.
- **Rifles:**
  - Every guard carries one. Take a rifle from a guard you've knocked out at night (5 rounds), or from the guardhouse rack (8 rounds; there are two).
  - With a rifle, Act on a guard in clear sight shoots him: the siren goes off, guards nearby come, and it costs +10 Weight.
  - A guard who sees you armed shoots at you.
- **The burn pit:** come up behind a guard at its edge and you can push him in. Only the fire flaring up is shown.
- **How it ends:** caught a third time, or still there after the fifth night, you're put in the line to the East Block, and that ending can't be avoided. Friends still in the cells at dawn are taken for good.

## Finding your way
- **Next:** a box at the top left always gives the one concrete thing to do now and where.
- **Ways out panel:** lists each route with its requirements, ticked or crossed, and where to get each one.
- **The guide:** amber footprints, a floating marker and an edge arrow lead to the current goal. Tap a line in "Ways out" to be guided there.

## Controls
| Key | Touch | Action |
| --- | --- | --- |
| WASD / Arrows | Thumb stick | Move (tilt the stick gently to creep) |
| 1 · 2 · 3, Shift | WALK / SNEAK / SPRINT | Change stance |
| E / Space (hold to work) | ACT | Talk, take, open, throw a scrap, knock out, shoot |
| Q | GROUP | Tell your friends to wait or follow |
| P / Esc, M | II | Pause, sound on/off |
| Mouse wheel, + / −, 0 | Pinch, or the + / − buttons | Zoom in and out (0 resets; the level is remembered) |

Pause menu: sound, *Chatter* (nearby only / off / all) and *Loudspeakers* (normal / quiet / off).

## Visual style
Mid-1990s European isometric 3D adventure games: polygonal characters in a hand-painted miniature world. All designs are original.
- **Characters:** low-poly figures with soft Gouraud shading, sculpted heads and individual faces.
  - Aren has a freshly shaven head (a faint dark shadow with a hairline) and a goatee.
  - Bram is heavier, darker and bearded.
  - Tomas is grey with glasses.
  - Mira wears a bun and a dark-blue scarf.
  - Aren and the two nearest people get full detail, and still figures are cached.
- **Environment:**
  - Dithered 64-texel textures: prefab metal barracks, concrete blocks, corrugated roofs, steel fence posts and towers.
  - Construction details, cutaway roofs, cast shadows, and a diorama base.

## Sound
- **Loudspeakers:** by day, after a modern two-tone chime, the facility PA plays classical recordings: Verdi's **Anvil Chorus** (*Il trovatore*) through the morning's work, then after the midday announcement Mussorgsky's **Bydło** (*Pictures at an Exhibition*, the heavy ox-cart), then quiet until the end-of-work announcement. Opened as a local file, without the recordings, an original synthesised anthem stands in.
- **Announcements:** at midday and just before the evening bell, the loudspeakers carry angry announcements in a made-up language, through a distorted megaphone.
- **Guard office radio:** at night it plays a slow original synth piece, faint from outside.
- **Siren and dogs:** a mechanical siren that spins up and winds down, and dog barks with distinct voices.
- **Ambience:** wind, fence hum, the generator, footsteps by surface, the burn pit, and sparse distant life.
- **Subtitles:** only for speech meant for you, and they fade when they cover a character.

## Audio credits
- `audio/siren.mp3`: a mechanical civil-defence siren (wavering tone), recorded in St. Paul, Minnesota by Techtonic, Wikimedia Commons (File:Civil-defense-siren-waver.ogg), public domain. A 40-second excerpt.
- `audio/dog-1.mp3`, `dog-2.mp3`, `dog-3.mp3`: excerpts of "Barking of a dog" and "Barking of a dog 2" by Amada44, Wikimedia Commons, licensed CC BY-SA 3.0 (https://creativecommons.org/licenses/by-sa/3.0/). Trimmed and loudness-normalised; these three excerpts are shared under the same licence.
- `audio/anvil-chorus.mp3`: Giuseppe Verdi, "Anvil Chorus" from *Il trovatore*, performed by Musopen, Wikimedia Commons (File:Giuseppe Verdi - Anvil Chorus.ogg), CC0 / public domain. Converted to mono and loudness-normalised.
- `audio/bydlo.mp3`: Modest Mussorgsky, "Bydło" from *Pictures at an Exhibition*, performed by the Skidmore College Orchestra, Wikimedia Commons (File:Skidmore College Orchestra - 07 - IV Bydlo Sempre moderato pesante.ogg), CC0 / public domain. Converted to mono and loudness-normalised.
- `audio/announce-day.mp3`, `announce-evening.mp3`: made-up words written for the game, spoken by the eSpeak NG speech engine (Esperanto phonetics, male variant) with a megaphone treatment.
- All other music and every other sound are synthesised in the browser and original to this game.
