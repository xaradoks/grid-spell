# Grid Spell

**Year:** 2026  
**Author:** viraible 
**Medium:** Browser-based interactive audiovisual instrument (HTML5 Canvas, Web Audio API, Vanilla JS)  
**Live:** [ссылка на GitHub Pages]

---

## What it is

The border becomes not a point of intersection but a source. A place that provokes Ratio most — where it rages and furiously whips up foam at the mouth. Inside the borders lives a life of its own, and it, too, has force.

A 10×10 grid cut from a loaded image. Each cell sounds by its own internal vertical: brighter top — higher, brighter bottom — lower. Black cells are silence you compose. Bent lines crackle. `GLOBAL MOD AMOUNT` is the depth of that breathing.

## How to use

1. Click **Play** (browsers block audio until first user gesture).
2. Load an image with the globe button.
3. Drag lines to bend them — the sound changes.
4. Make cells black (via **Random** or by dragging) — they become pauses.
5. `Y-AXIS`: **Pitch / Spread / Register / Drift** — how the cell's internal vertical maps to height.
6. `GLOBAL MOD AMOUNT`: `0` — flat 300 Hz (silence stands out), `100` — full Y-modulation.

## Controls

| Control | Range | What it does |
|---|---|---|
| BPM | 40–240 | Playhead speed, globe rotation |
| Y-AXIS | Pitch / Spread / Register / Drift | How `weightedY` maps to pitch |
| BOUNDARY WAVE | Noise / Sine / Square / Saw / Triangle | Oscillator type |
| BOUNDARY MODE | Warp / Shift | Visual only (warp bends image, shift slides it) |
| GLOBAL MOD AMOUNT | 0–100% | Depth of Y-modulation |
| AMP / FREQ / SEED | 0–100 / 1–20 / 0–100 | Deformation of the selected line |
| Reset (square) | — | Lines + image back to original |
| Random (diamond) | — | Shuffle cells + random black holes |

## Notes

Built in dialogue with an AI assistant (Claude). Concept, design, sound decisions, final assembly — the author's.

---

## License

[выбери: MIT / CC BY-NC / All rights reserved — по желанию]
