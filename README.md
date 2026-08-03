# Patriot Party News — The Underground (v2 mockup)

Single-file mockup of the new PPN website, voiced per the **PPN Voicing Playbook
Vol. 01** ("the broadcast is the trailer; the Underground is the show").

- `index.html` — the full mockup. Self-contained (inline CSS/JS, Google Fonts).
  Open directly in a browser, or paste into the Elementor HTML widget route.
- `HIGGSFIELD-MOTION-PROMPTS.md` — draft prompts for the three motion slots.
  **Nothing generated yet — drafts for discussion only.**

## Countdown config

The Patriot Drive Time countdown target is one line at the top of the script in
`index.html`:

```js
const DRIVE_TIME_LAUNCH = new Date('2026-08-03T15:00:00-04:00'); // Mon 3 PM ET
```

- 3 PM ET (August = EDT): `-04:00`
- 3 PM MST: `-07:00`
- Next Monday: change the date to `2026-08-10`

After the moment passes, the countdown auto-flips to a "THE ROOM IS OPEN —
DRIVE TIME IS LIVE" state and the CTA changes to "Walk In Now".

## Conversion changes vs. the old site (playbook mapping)

| Section | Playbook lever |
|---|---|
| Hero "This is the door" | Master line + Hook 02 (The Door), identity-first opening |
| Live-inside rotator | Hook 04 — one specific thing at a time, loss aversion |
| Drive Time countdown | New product launch + specificity ("Monday, 3 PM ET") |
| "Today, on the other side of the door" | Hook 04 program wire — Coffee with Chas, Talk Time, giveaway |
| State rooms | Hook 01 — isolation reversal ("your neighbors are already in it") |
| Algorithm split | Hook 03 — calm censorship frame, no drama |
| Midterms band | Urgency: live day-counter to Nov 3, "real talks with real people" |
| Asked in chat | Objection handling verbatim from playbook §06 |
| The cover charge | Price reframe ($12.99 = cover, "less than a tank of gas"), Hook 06 walk-away + "most don't", Hook 07 powered-by-members |

Every CTA points to https://join.patriotchute.com/ and repeats the walk-away
line: **30 days free · code PATRIOT10X · cancel anytime — most don't.**
