# 01 - HTML Reel Master Prompt

Generates a complete 9:16 animated reel as a single HTML file. Fill in the brackets, paste into your AI tool, then open the resulting file in a browser (or screen-record it).

## Prompt

```
You are an expert motion designer and front-end developer.

Build a 9:16 animated reel as ONE self-contained HTML file (HTML + CSS + vanilla JavaScript only, no external libraries, no external images).

TOPIC: [TOPIC]
TOTAL LENGTH: [30-45] seconds
STYLE: [e.g. clean flat illustration, dark cinematic, bright cartoon]
COLOR PALETTE: [e.g. deep navy #0b1d3a, warm gold #f5b942, off-white #f4f1ea]
FONT: [e.g. bold sans-serif system font]
BADGE TEXT (top corner): [CHANNEL NAME]

SCRIPT (one line per scene):
Scene 1 (hook): [line]
Scene 2: [line]
Scene 3: [line]
...
Final scene (closing line / call to action): [line]

TECHNICAL RULES:
1. Use a fixed 1080x1920 stage and scale it to fit any screen with CSS transform, keeping the 9:16 ratio and centering it.
2. Keep all important text and visuals inside safe zones: leave ~150px at the top and ~350px at the bottom free for app UI.
3. Define scenes in one JavaScript array: { duration, caption, build() } so timing is easy to edit.
4. Show each caption as large, high-contrast text, animated word by word.
5. Use smooth easing (ease-in-out) and a different transition between scenes (fade, slide, zoom). Never repeat the same transition twice in a row.
6. Draw visuals with inline SVG and CSS shapes. Add subtle constant motion (floating, pulsing, slow zoom) so no frame is ever static.
7. Add a thin progress bar at the bottom of the stage.
8. Add a Play / Replay button shown before start and after the last scene.
9. Add an optional voiceover hook: if a file named voiceover.mp3 exists, play it in sync; otherwise run silently.
10. The first scene must grab attention within 2 seconds with the boldest visual and the shortest caption.

OUTPUT:
Return ONLY the complete code in a single code block. No explanation before or after.
```

## Tips

- Generate the file in parts for longer reels (scenes 1-4, then 5-8) and ask the AI to keep the same palette and scene array.
- Screen-record at 1080x1920 to export as a video.
