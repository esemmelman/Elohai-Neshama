# Elohai Neshama

An interactive Hebrew tutorial for the prayer *Elohai Neshama*, set in Frank Ruhl Libre.

The page includes syllable practice, word- and line-level audio playback, a browser-based recording studio, local recording storage, and support for published audio files on GitHub Pages.

## Run locally

Serve the folder from a local web server so microphone access and `audio/manifest.json` loading work consistently:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish recordings

Use **Recording studio → Export all as ZIP**, then extract the exported audio files and manifest into the `audio` folder before committing them. See [`audio/README.md`](audio/README.md) for details.
