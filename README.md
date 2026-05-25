# WaveRip

A YouTube to MP3 / MP4 converter I built as a frontend project. Paste a YouTube link, pick your format and quality, and download. Simple as that.

The backend isn't hooked up yet — right now it runs in demo mode with simulated progress. I'm planning to connect it to a Python/Flask backend using yt-dlp at some point.

---

## What it does

- Paste any YouTube URL and fetch video info
- Switch between MP3 (audio) and MP4 (video)
- Choose quality — 128/192/320kbps for audio, 720p/1080p/4K for video
- Shows a thumbnail preview with the video title and duration
- Animated progress bar during conversion
- Fully responsive, works on mobile too

---

## Tech used

- HTML, CSS, vanilla JavaScript
- No frameworks, no build tools — just one file
- Google Fonts (Syne + DM Mono)

---

## Running it

No setup needed, just open the file:

```
open youtube-converter.html
```

Or drag it into any browser.

---

## What's next

To make the downloads actually work I need to build out the backend. The plan is:

- Python + Flask for the server
- yt-dlp to handle the actual downloading
- Hook up the two TODO points in the JS to real API endpoints
- Host it somewhere like Railway or Render

---

## Note

This is for personal/educational use only. Downloading YouTube videos may go against their terms of service so use it responsibly.
