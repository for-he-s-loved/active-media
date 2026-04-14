# Active Media

Two-in-one browser toolkit for video creators — **no server, no uploads, no installs**.

## 🎬 Documentary Generator ← NEW

Type any subject, upload your own footage, and get a full 10+ minute narrated documentary video, assembled automatically:

1. **AI Script** — GPT writes a compelling multi-section documentary script
2. **AI Narration** — OpenAI TTS reads the script in a documentary voice
3. **Your Footage** — Upload your own video clips (YouTube downloads, screen recordings, anything) and the tool auto-clips them to fit each section
4. **Auto Compose** — FFmpeg WASM stitches clips + narration with title cards, fades, and proper timing
5. **Download** — grab the finished MP4 and upload to YouTube

### Requirements
| Key | Where to get it | Cost |
|-----|-----------------|------|
| OpenAI API key | [platform.openai.com/api-keys](https://platform.openai.com/api-keys) | Pay-as-you-go (~$0.10–$0.50 per documentary) |

Keys are stored in your browser's localStorage and sent only to their respective APIs.

Upload as many video clips as you like — they're distributed across sections automatically. Sections without clips get a stylish generated background.

---

## ⚡ Jarvis Video Edit Portal

Beat-synced automatic video editor that runs **100% in your browser**.

### Features
- **Auto Edit** — drop any video + music → instant beat-synced reel
- Detects bass/kick, snare, hi-hat, and energy peaks
- Scores every scene for motion and color energy — picks the coolest parts
- Transition styles: Auto zoom-punch, Hard cuts, Soft fade, Center Grow
- Flash on strong beats, color grading, vignette
- **Style Match** — copy pacing and cuts from a reference video onto your own footage
- Download result as MP4

### How to use
Open the GitHub Pages URL and:
1. Choose your source video
2. Choose a music file (MP3/WAV/M4A)
3. Pick transition style and output length
4. Press **⚡ Create Edit** — processing runs in your browser via WebAssembly FFmpeg

First run downloads ~30 MB of FFmpeg WASM (cached by your browser after that).

## Live Site

🌐 **https://for-he-s-loved.github.io/active-media/**

Deployment is automated via GitHub Actions — every push to `main` redeploys the site.
