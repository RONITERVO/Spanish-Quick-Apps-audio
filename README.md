# Spanish Quick Apps audio

Full-quality generated English and Finnish narration assets for [Spanish Quick Apps](https://github.com/RONITERVO/Spanish-Quick-Apps).

This companion repository keeps the educational application's GitHub Pages deployment below the platform's published-site size limit. Files under `assets/syncvoice/` are deterministic outputs of [SyncVoice](https://github.com/RONITERVO/syncvoice); application source and the canonical narration manifest remain in the main repository.

## Published library

- 6,415 English MP3/transcript pairs
- 6,415 Finnish MP3/transcript pairs
- 24 kHz, 96 kbps MP3 output, unchanged from the SyncVoice generation profile
- runtime manifest at `assets/syncvoice/manifest.json`

GitHub Pages publishes this repository at `https://ronitervo.github.io/Spanish-Quick-Apps-audio/`. The application and this asset site share the same `ronitervo.github.io` origin, while separate repositories keep each published site below GitHub Pages' size limit. Git LFS is intentionally not used because GitHub Pages does not publish LFS objects.

Merge and publish this repository before the dependent Spanish Quick Apps narration PR. Future regeneration is resumable; SyncVoice validates both the MP3 and transcript in this output root before skipping an entry.
Full-quality generated narration assets for Spanish Quick Apps
