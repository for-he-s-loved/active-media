# Jarvis Video Edit Portal

Beat-synced automatic video editor that runs **100% in your browser** — no server, no uploads, no installs.

## Features
- **Auto Edit** — drop any video + music → instant beat-synced reel
- Detects bass/kick, snare, hi-hat, and energy peaks
- Scores every scene for motion and color energy — picks the coolest parts
- Transition styles: Auto zoom-punch, Hard cuts, Soft fade, Center Grow
- Flash on strong beats, color grading, vignette
- **Style Match** — copy pacing and cuts from a reference video onto your own footage
- Download result as MP4

## How to use
Open the GitHub Pages URL and:
1. Choose your source video
2. Choose a music file (MP3/WAV/M4A)
3. Pick transition style and output length
4. Press **⚡ Create Edit** — processing runs in your browser via WebAssembly FFmpeg

First run downloads ~30 MB of FFmpeg WASM (cached by your browser after that).

## Host on GitHub Pages
1. Create a new GitHub repo (e.g. `video-edit-portal`)
2. Push the contents of this folder to the `main` branch
3. Go to repo **Settings → Pages → Source → Deploy from branch → main / root**
4. Your portal will be live at `https://YOUR_USERNAME.github.io/video-edit-portal/`
