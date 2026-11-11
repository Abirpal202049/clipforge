# ClipForge — Video Editor

A free video editor that runs entirely in your browser. Your videos, photos and music never leave your device — nothing is uploaded.

**Open it:** https://YOUR-USERNAME.github.io/clipforge/

## Features
- **Timeline:** multiple video, overlay, caption and audio tracks · trim · split · duplicate · delete · freeze frame · undo/redo · snapping
- **Animate:** keyframes (position, scale, rotation, opacity) · in/out animations · loops · text animations (typewriter, letters, word pop, wave)
- **Look:** crop · masks (7 shapes + text) · 16 filters · adjustments · 17 effects (glitch, VHS, RGB split, shake, cartoon, sketch…) · blend modes
- **Transitions:** 16 transitions between clips (dissolve, wipes, push, zoom, circle, glitch…)
- **Speed:** 0.1×–8× · speed curves (Montage, Hero, Bullet…) · reverse
- **Audio:** music · 18 built-in sound effects · voiceover recording · volume & fades · noise / hum reduction · voice enhance · extract audio
- **Text & captions:** 10 text styles · stickers · captions from .srt/.vtt files or from a pasted script
- **Smart tools:** split at scene changes · remove silences · auto-edit to the music beat · auto enhance · green screen · AI person cutout · motion tracking
- **Export:** 16:9, 9:16, 1:1, 4:5, 4:3 · 720p, 1080p, 2K, 4K · 24/30/60 fps · MP4 or WebM

## Tips
- Works best in **Chrome or Edge** on a laptop/desktop.
- Export renders in real time — keep the tab open and visible until it finishes.
- Projects aren't saved between visits; export when you're done.

## Tech
Plain HTML, CSS and JavaScript in a single `index.html` — no build step. Canvas 2D rendering, Web Audio, MediaRecorder for export, [Lucide](https://lucide.dev) icons, and Google's [MediaPipe](https://github.com/google/mediapipe) (Apache-2.0) for the AI person cutout.
