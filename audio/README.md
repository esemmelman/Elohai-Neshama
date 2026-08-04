# Published word recordings

Record the Hebrew words and prayer lines in the page's Recording Studio, then choose **Export all as ZIP**.

To publish the recordings:

1. Extract the ZIP.
2. Copy its `word-XX` and `line-XX` audio files into this folder.
3. Replace this folder's `manifest.json` with the exported `manifest.json`.
4. Commit and push the complete `audio` folder with `index.html`.

The webpage loads these published recordings automatically. Recordings made later in a visitor's browser stay local and override the published version on that device. Deleting a local replacement restores the published recording.
