# 03 - Camera Drift Prompt

Plans a slow zoom or drift for every still image so the reel feels alive. Works with any video editor (CapCut, DaVinci Resolve, Premiere, etc.).

## Prompt

```
You are a video editor planning camera motion for a vertical 9:16 reel made from still images.

TOTAL SCENES: [NUMBER]
REEL LENGTH: [SECONDS] seconds
MOOD: [e.g. emotional and slow, energetic and fast]

SCENES (one line each, with duration):
Scene 1 - [description] - [X] sec
Scene 2 - [description] - [X] sec
...

For EVERY scene, return one row in a table with these columns:
Scene | Motion type | Start scale | End scale | Direction / position shift | Easing | Why this motion

RULES:
1. Motion types allowed: slow zoom in, slow zoom out, drift left, drift right, drift up, drift down, zoom in with slight drift.
2. Scale must stay between 100% and 120%. Use subtle values (e.g. 100% -> 110%) for emotional scenes and larger values for dramatic moments.
3. Never use the same motion on two scenes in a row.
4. Zoom in toward the subject on emotional or important lines. Zoom out to reveal a wider situation or a surprise.
5. The hook scene should have the fastest, most noticeable motion. The final scene should end with a slow, calm motion.
6. Use ease-in-out for every move so there are no sudden starts or stops.
7. Keep the main subject inside the safe zone (not in the bottom 25% or top 10%).

After the table, add:
- A 3-line summary of the overall motion rhythm.
- A short note on any scene where the motion should be sped up or slowed down.
```

## Quick reference for editors

| Feeling | Motion | Scale |
|---|---|---|
| Emotion / intimacy | Slow zoom in | 100% -> 108% |
| Reveal / surprise | Zoom out | 112% -> 100% |
| Journey / time passing | Drift left or right | 105% fixed, shift 6-8% |
| Tension | Zoom in + slight drift | 100% -> 115% |
| Calm ending | Very slow zoom out | 106% -> 100% |
