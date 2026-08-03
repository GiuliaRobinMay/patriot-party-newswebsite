# Higgsfield Motion Prompts — DRAFTS FOR DISCUSSION

**Status: NOT generated. Nothing has been run. No credits spent (balance: 922).**
These are proposals for the three moving images ("motion slots") in the new site.
Edit freely — nothing happens until you explicitly approve.

Suggested pipeline per slot: 1 still image (Soul 2 / Nano Banana Pro) → animate the
approved still with Seedance 2.0 (image-to-video, `generate_audio: false`, 5s, 16:9,
mode `std`, 720p or 1080p). We can preflight the exact credit cost with a free
`get_cost` check before running anything.

---

## Slot 01 · HERO — "The Door"
**Where:** Full-screen hero background.
**Voicing hook:** Hook 02 — "You're either in the room or watching the door."

**Image prompt (draft):**
> Cinematic photograph looking down a dark wood-paneled hallway toward a heavy oak
> door standing slightly ajar, warm amber light spilling through the gap onto the
> floorboards, faint silhouettes and an American flag just visible inside the room
> beyond, dust motes floating in the shaft of light, deep navy-blue shadows, brass
> door handle catching the light, moody film-noir atmosphere, anamorphic lens, rich
> contrast, color palette of dark navy, cream, brass and deep flag red.

**Motion prompt (draft):**
> Extremely slow dolly-in toward the door, light through the gap gently flickering
> as if people are moving inside the room, dust motes drifting through the light
> beam, subtle warm glow pulsing. No camera shake. Loopable, calm, cinematic.

---

## Slot 02 · DRIVE TIME — "The Ride Home"
**Where:** Background of the Patriot Drive Time launch/countdown section.
**Voicing hook:** Hook 04 — the specific thing (new 3 PM room).

**Image prompt (draft):**
> Cinematic golden-hour photograph from inside an American pickup truck cab driving
> a wide open highway at sunset, weathered hands on the steering wheel, smartphone
> mounted on the dashboard glowing softly with an audio waveform, sun flare through
> the windshield, long straight road ahead through big-sky country, warm amber and
> deep navy tones, film grain, anamorphic lens flare, Americana road-trip mood.

**Motion prompt (draft):**
> Road and landscape moving past steadily, sun flare shifting gently across the
> windshield, waveform on the phone screen pulsing as if a live voice room is
> playing, hands steady on the wheel. Smooth, warm, loopable. No cuts.

---

## Slot 03 · STATE ROOMS — "Fifty Rooms Alight"
**Where:** Visual panel of the "Your state has a room" section.
**Voicing hook:** Hook 01 — isolation reversal ("your people are already inside").

**Image prompt (draft):**
> Dark cinematic data-art visualization of the United States map made of tiny
> glowing ember-like points of warm amber light on a deep navy-blue background,
> all fifty states outlined by faint brass constellation lines, roughly fifty
> brighter beacons pulsing in state capitals connected by thin threads of light,
> subtle red accent glows, atmospheric haze, premium editorial style, no text,
> no labels.

**Motion prompt (draft):**
> Slow, almost imperceptible zoom-in. The fifty beacons breathe and pulse at
> slightly different rhythms like a living network, occasional faint threads of
> light traveling between states, embers shimmering. Loopable, ambient, alive.

---

## Open questions to settle before generating
1. Approve/adjust the three concepts (door / highway / map) — or swap any scene.
2. Resolution: 720p (cheaper) vs 1080p (crisper on large screens).
3. Whether slot 01 should include any human presence (silhouettes) or stay empty.
4. Run `get_cost` preflight first and confirm total budget before any generation.

## How they drop into the site
Each slot in `index.html` contains a commented-out `<video>` tag
(`assets/slot-0X-*.mp4` + poster). Uncomment, add the files, done. The CSS
placeholder animations remain as the fallback/loading state.
