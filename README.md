# Vryt

*Verse + Write.* Vryt turns song lyrics into moving text patterns, in time with the music.

**Live:** https://exquisite-marigold-950d56.netlify.app

## What it does

- Finds time-synced lyrics for a song (via LRCLIB), or lets you paste your own.
- Writes each lyric line along a shape on a black canvas, changing as the song plays.
- Plays along with a YouTube link or an audio file from your device.
- Exports the result as a video.

## Patterns

- **Mixed:** cycles through the whole set: lines, arrows, heart, spiral, infinity, XX
- **Single line**
- **3 horizontal lines**
- **Vertical + horizontal**

## How to use

1. Type a song name and artist, then press **Search & match**.
2. Load the music: paste a YouTube link, or choose an audio file.
3. Press **Play**. Use **Timing shift** if the lyrics are slightly early or late.
4. Press **Full screen** (or double-click the canvas) for a clean view.
5. Press **Export** to record a video. It records in real time, so keep the tab open.

Sound is included in the export only when you load an audio file. YouTube audio can't be captured by the browser.

## Run locally

It is a single file with no dependencies. Open `index.html` in a browser.

## Deploy

Drop the folder on Netlify, or connect this repo for automatic deploys on every push.
