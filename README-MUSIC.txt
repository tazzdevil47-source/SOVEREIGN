SOVEREIGN MUSIC PATCH

This keeps your original app intact and adds:
- A tiny original fantasy ambience file: music/imperial-ambience.mp3
- A bottom-right music toggle button
- No autoplay
- preload="none" so it does not slow app startup
- Service worker cache bump to sovereign-v5-music

Test locally:
npx serve .

Deploy:
Upload index.html, sw.js, manifest.json, and the music folder.
Clear old PWA/browser cache once after upload.