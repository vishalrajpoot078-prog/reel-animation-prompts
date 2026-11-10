# 02 - AI Image Scene Prompt

Keeps every image in a reel looking like it belongs together. Define the style and character once, then reuse them in every scene prompt.

## Step 1: Style bible (write once per reel)

```
STYLE BIBLE
Art style: [e.g. 3D cartoon, soft lighting, clean shapes]
Color palette: [3-5 colors]
Lighting: [e.g. warm golden hour, soft rim light]
Mood: [e.g. emotional, inspiring, mysterious]
Aspect ratio: 9:16 vertical
Quality: highly detailed, sharp focus, consistent rendering
```

## Step 2: Character sheet (skip if there are no recurring characters)

```
CHARACTER: [NAME]
Age and build: [e.g. 30-year-old man, slim, short black hair]
Clothing: [exact outfit, same in every scene]
Distinctive detail: [e.g. round glasses, red scarf]
```

## Step 3: Scene prompt template (one per scene)

```
[STYLE BIBLE pasted here]
[CHARACTER description pasted here, if needed]

SCENE [NUMBER]: [what is happening, in one clear sentence]
Setting: [location, time of day]
Camera: [e.g. medium shot, eye level]
Composition: subject in the center-upper area, leave the bottom 25% and top 10% of the frame empty for captions and app UI
Emotion: [what the viewer should feel]
```

## Negative prompt (paste after every scene prompt, if your tool supports it)

```
no text, no watermark, no logo, no extra fingers, no distorted faces, no blurry details, no cropped head, no split frames
```

## Tips

- Always generate a taller or larger image than the final frame so the zoom and drift in `03-camera-drift-prompt.md` has room to move.
- If a character changes between scenes, re-paste the character sheet word for word.
- Keep one scene = one idea = one image.
