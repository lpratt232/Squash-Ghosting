# Ghosting — Squash Court Trainer (PWA)

A mobile-first squash ghosting drill app that runs entirely in the browser.

## Features
- Random court position every N seconds (configurable 3–60s)
- Session timer with auto-stop (30s to 30min)
- 6 or 8 court positions (adds serve box positions)
- Audio beep on each position change
- Settings saved between sessions
- Works offline once installed
- Screen stays awake during sessions

## Install on Android

### Option A: GitHub Pages (free, easiest)

1. Create a GitHub account at github.com (if you don't have one)
2. Create a new repository (e.g. "ghosting")
3. Upload all 5 files from this zip into the repository:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
4. Go to **Settings → Pages → Source** and select "main" branch
5. Your app will be live at `https://yourusername.github.io/ghosting/`
6. Open that URL on your Android phone in Chrome
7. Tap the **⋮ menu → "Add to Home Screen"**
8. It now launches fullscreen like a native app!

### Option B: Netlify (free, drag-and-drop)

1. Go to https://app.netlify.com/drop
2. Drag the entire unzipped folder onto the page
3. Your app gets a URL like `https://random-name.netlify.app`
4. Open on Android Chrome → **⋮ menu → "Add to Home Screen"**

### Option C: Any web server

Just upload the 5 files to any static web hosting (Firebase, Vercel, your own server, etc.) and access via HTTPS.

## Files
- `index.html` — The complete app (single HTML file)
- `manifest.json` — PWA manifest (app name, icons, display mode)
- `sw.js` — Service worker (enables offline use)
- `icon-192.png` — App icon (192×192)
- `icon-512.png` — App icon (512×512)
