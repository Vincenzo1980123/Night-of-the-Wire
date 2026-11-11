# Night of the Wire

An isometric stealth adventure in a single HTML file, playable on desktop and on phones (iPhone included). It's set in Grauhof, a fictional camp run by "the Directorate". By day you do forced labour that helps the people who keep you there. By night you try to get yourself and three friends, Mira, Tomas and Bram, through the wire.

Open `index.html` in a browser. There's nothing to build or install.

`prototype.html` is the standalone art-direction prototype (a yard, a barrack you can walk into, a character turntable) that the game's current look was approved from.

> Content note: the game depicts a fictional extermination camp, forced labour and the line of people walked into the East Block. Nothing graphic is shown, but it is meant to be heavy.

## The camp
- **North:** the main gate in the outer fence, the open strip in front of it, the workshop, the power house and the guard office.
- **Middle:** Blocks A, B and C, the kitchen yard, the cells, and the passage into the East compound.
- **South section**, open to the rest of the camp: the Kantine, the Lazarett (infirmary), the water basin with its wash troughs, Blocks D and E, and the Wachstube (guardhouse) with its rifle rack.
- **East compound:** the East Block and the fire pit, with a long fenced corridor down to the arrivals gate in the south fence.
- **Outside the south fence:** the railway ramp, a small station, two tracks and a standing train of cattle wagons with a steaming locomotive. At night a whistle announces another line, which walks from the ramp through the arrivals gate to the East Block.
- Every section has lamp posts with horn loudspeakers, so the day programme carries across the whole camp.

- There are no inner fences: the only fenced area inside the camp is the East compound around the East Block.

## Health and what to do next
- **Health** (under Breath) drops when guards beat you (−15), when you're caught (−25) and when you're shot (−45). A rifle hit no longer means instant capture: you're wounded and can keep going. If your health runs out you collapse, which counts as being caught, and you wake at 40.
- **Low health** (red, below 35) slows you down, shortens your breath and reddens the edges of the screen.
- **Healing:** slowly over time, faster resting in a barrack at night or while sleeping. Doktor Lamm in the Lazarett treats you once a day (+35).
- **Next:** a box at the top left always says the one concrete thing to do now and where. For example: "Find Tomas (he's in Block C), or do the East Block job to learn the breaker", "Get wire cutters (workshop job, or Bram at night) or a blanket (Lazarett shelf, now empty)", "Dawn is coming. Get into a barrack before roll call."
- **Ways out:** under each route, its requirements with ✓ or ✗ and where to get each one.

## Rifles
- **Every guard is armed:** rifle slung on his back on patrol, raised to his shoulder when he chases.
- **Getting one:** knock a guard out at night and take his rifle (5 rounds), or steal one from the Wachstube rack (8 rounds; there are two).
- **Shooting:** with a rifle, Act on a guard within about 8 tiles in clear sight shoots him. Accuracy drops with distance. He falls and fades; nothing graphic is shown. The shot sets off the siren, alerts every guard within about 16 tiles, adds +10 Weight and turns his dog loose. A replacement arrives at dawn.
- **Being armed:** any guard who sees you armed outside a barrack chases you, stops, aims and fires. Each hit costs 45 health; if it takes the last of it, you're caught and lose the rifle.
- **Ether:** the Lazarett job gives you a vial. Your next knockout lasts until morning.

## A day in Grauhof
A working day lasts about 8 minutes (06:00 to 18:00), as long as the loudspeaker programme, so every record plays to the end. Nights last 3½ minutes.

- **Roll call (06:00):** choose today's work. The jobs are spread across the camp: the workshop and the guard office in the north, the Kantine, the Lazarett and the laundry at the water basin in the south section, and the East Block detail in the east.
- Every job helps the oppressor. Some give you something; the heaviest gives you the most.
- **Finding your work:** once you've chosen, faint amber footprints lead from Aren to the work place along a walkable route, and a marker floats over the spot (visible over roofs). When the spot is out of view, an arrow beside Aren points the way with the distance. Inside the East Block the footprints lead to the next stain. The guide disappears while you work and once the shift is done.
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
- **Escape:** cut the power and get over the outer fence, or open the main gate with the keycard while the power is on, or tunnel out. Then reach the forest with whoever is still with you.
- **Caught:** the first two times you're thrown back in your barrack. The third time, you are put in the line to the East Block. You can't leave the line, and the ending can't be avoided.
- **Selection:** after the fifth night, Block A is selected. If you've only worked and never escaped, you end up in the line anyway. Five full days played without skipping take about 30 minutes; finishing work early or sleeping through a night makes the time pass faster.
- **Friends:** friends still in the cells at dawn are taken east and are gone for good.

## Your own way out
Grauhof is open: there's no fixed order and no required route.
- **Work is optional.** At roll call you can *slip away* instead of taking a job. The barracks stay safe, but any guard who spots you idle in the yard gives you five seconds, then beats you back inside. At the evening count you take +6 Weight.
- **Through the wire:** kill the power (Tomas, or the breaker the East detail shows you), then get over the dead outer fence with the wire cutters or a blanket thrown over the barbs.
- **Through the main gate:** the gate keycard (guard office job, or Mira at night) opens the main gate in the outer fence, but only while the power is on: its lock is electric. So the lights and searchlights stay on.
- **Under it:** dig a tunnel under the bunks in Block A, in a skipped day or at night. It takes about two and a half minutes of digging, and less with Bram helping. Each morning there's a chance the inspection finds it and fills it in.
- **In daylight:** every action works by day too, but a dead fence in daylight sets off the sirens at once.
- **Friends are optional.** Recruit Mira, Tomas and Bram and bring them, ask them to come with you even in daylight, or go alone. The ending reflects who made it, how and when.
- **The fire pit:** beside the East Block a pit burns day and night. Come up behind a guard standing at its edge and you can push him in. Nothing is shown but the fire flaring up. It costs +12 Weight, nearby guards hear it, his dog is loose, and at dawn a replacement takes his post.
- There are only two blankets, on the linen shelf in the Lazarett at the far south of the camp. The bunks don't give any. The "Ways out" panel tracks every route.
- **Finding your way:** amber footprints, a floating marker and an edge arrow lead to the current goal. By day that's your work. Otherwise it's the next sensible step, such as the generator, the bunks for blankets, the fence, or the dig spot once you've started the tunnel. Tap any line in "Ways out" to be guided there instead; tap it again to stop. The guide resolves to what you actually need: no keycard and no blanket means it leads you to the bunks first. The dig spot (a loose floorboard in Block A) and the tunnel exit are also shown on the minimap.

## Visual style
The look is mid-1990s European isometric 3D adventure games: polygonal characters walking through a hand-painted miniature world. All designs are original.
- **Characters:** real-time low-poly 3D figures with soft Gouraud shading in stepped palette ramps, lit from a single direction. Heads are sculpted ovals with individual faces: nose, set-in eyes with lids, brows, mouth, ears, age lines, hair, beards and glasses vary per person, and every prisoner and guard gets a slightly different face. Aren is bald with a goatee; Bram is heavier, darker and fully bearded; Tomas is grey with glasses; Mira wears her hair in a bun and a red scarf. Posture shows state: prisoners stoop, the people in the line walk with their heads bowed, guards stand upright. Poses blend smoothly between standing, walking, running, sneaking, sitting, kneeling to scrub and lying down.
- **Detail levels:** Aren and the two people nearest him get full faces; everyone further away uses a lighter version of the same model. Anyone standing still is painted once and reused until they move.
- **Environment:** procedurally generated, dithered 64-texel textures (concrete block with a plinth, weathered planks, tar paper, corrugated iron, terracotta, brick, dirt with pebbles, gravel, grass), with construction details: corner posts, window sills, fascia and barge boards, ridge caps, door frames and steps, double bunks. The camp sits on a diorama base, with world-scale ground variation, puddles, cast shadows and contact shadows at the base of walls.
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
- **Siren:** an old motor-driven air-raid siren. It spins up from a low growl, wails up and down on two tones a minor third apart, echoes off the barracks, and winds down slowly after it's switched off.
- **Dogs:** barks are synthesised sample by sample like a real voice: a rough, uneven throat source whose pitch jumps up and falls away, shaped by mouth resonances that open and close, with a breath burst at the onset and a slap-back echo outdoors. Three dog voices (different sizes), four variations each plus a growl, generated once when you press Start. Dogs bark at random, louder the nearer they are; others bark in the distance. The pit crackles and roars when you're close.
- **Camp loudspeakers:** horn speakers on the lamp posts run the day's programme: a chime and the day's march (a real 78 rpm record; "Alte Kameraden" on odd days, "Defilier-Marsch" on even days). At midday comes a chime and a German camp announcement ("Achtung, Achtung! Hier spricht die Lagerleitung…"), then the march again from the top. Shortly before the evening bell the music is cut for the end-of-work announcement ("…Alle Kommandos treten zum Abendappell an."). Everything goes through overdriven horn speakers with echoes across the yard, and it's muffled indoors. Pause → *Loudspeakers*: normal / quiet / off.
- **The gramophone:** in the evening and at night, the guard office gramophone plays an original slow waltz in the style of a 1940s German film song: a wordless contralto, plucked bass and chords, soft strings, on a worn 78 (narrow bandwidth, wow and flutter, hiss, crackle, a tick each turn, the run-out groove before it starts again). It's synthesised in the browser and composed for the game; the famous songs of that era are still under copyright. You hear it clearly inside the office, faint and muffled across the yard.
- **Ambience:** kept quiet and sparse. Wind with slow gusts, muffled inside. The electric fence hums when you're near it, and the generator thrums by the power house (both stop when the power dies). Footsteps change with the surface and with sneaking or sprinting. Distant life comes in at long intervals: work clanks and crows by day, crickets, an owl, far-off dogs and a train at night, and coughs and creaking bunks in the barracks.
- **Less text on screen:** by default only speech meant for Aren gets subtitles: friends, guards warning or chasing you, people you talk to. Background chatter is subtitled only from people right beside you, at most one line every few seconds; otherwise a small mark above the speaker shows who's talking. Pause menu → *Chatter*: nearby only / off / all. Subtitles are compact and turn see-through whenever they overlap Aren or the people near him.
- **Subtitles:** speech appears as film-style subtitles at the bottom, at most two lines at once, and only from people within earshot. Above a character's head there's only a small marker showing who is talking: dots for whispers, a red mark for shouts.
- **Action prompt:** sits just above the subtitles, with a faint ring on the floor under whatever it refers to.

## Audio credits
- `audio/alte-kameraden.mp3`: "Alte Kameraden" (Carl Teike, 1889), historical 78 rpm shellac recording by the Anker-Orchester (Anker 5387-10815), from the CC0-CH collection on Wikimedia Commons (File:Anker-5387-10815.ogg), public domain / CC0. Converted to mono MP3 and loudness-normalised.
- `audio/defilier-marsch.mp3`: "Defilier-Marsch" (Carl Faust), historical 78 rpm recording by the Anker-Orchester (Anker 5387-10819), CC0-CH collection on Wikimedia Commons (File:Anker-5387-10819.ogg), public domain. Converted to mono MP3 and loudness-normalised.
- `audio/night-record.mp3`: waltz from the operetta *Drei alte Schachteln* (Walter Kollo, 1917), historical 78 rpm recording by the Dacapo-Lyrophon-Orchester (Dacapo-Lyrophon 20580), CC0-CH collection on Wikimedia Commons, public domain. Mono MP3, loudness-normalised.
- `audio/siren.mp3`: a mechanical civil-defence siren (wavering tone), recorded in St. Paul, Minnesota by Techtonic, Wikimedia Commons (File:Civil-defense-siren-waver.ogg), public domain. A 40-second excerpt.
- `audio/dog-1.mp3`, `dog-2.mp3`, `dog-3.mp3`: excerpts of "Barking of a dog" and "Barking of a dog 2" by Amada44, Wikimedia Commons, licensed CC BY-SA 3.0 (https://creativecommons.org/licenses/by-sa/3.0/). Trimmed and loudness-normalised; these three excerpts are shared under the same licence.
- `audio/announce-day.mp3`, `announce-evening.mp3`: fictional camp announcements written for the game, spoken by the eSpeak NG speech engine with the MBROLA de6 German voice, with a microphone click, mains hum and room echo added. The MBROLA voice data is free for non-commercial, non-military use.
- All other music and sounds (chime, ballad, fire, wind, footsteps and the rest) are synthesised in the browser and original to this game. Each recording above falls back to a synthesised version if it can't load.
