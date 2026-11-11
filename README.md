# AUREX Downloader

A lightweight browser-based media workspace with two modes:

- **YouTube link:** embeds public videos using YouTube's official player and links to YouTube/YouTube Studio. For your own channel uploads, use YouTube Studio → Content → ⋮ → Download when available.
- **Direct media:** previews and downloads direct media file URLs when the host and browser allow it.

## Supported direct media formats
- Video: MP4, WebM, MOV, M4V
- Audio: MP3, M4A, OGG, WAV, AAC

## Run locally
Open `index.html` in a modern browser, or serve this folder with any static web server.

## Deploy with GitHub Pages
1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. The site will be published at `https://notgamershubh.github.io/aurex-downloader/`.

## Important
The YouTube mode uses the official embedded player; it does not extract streams or provide arbitrary YouTube downloads. Download YouTube videos only where you own the content, have permission, or YouTube explicitly provides a download option. This project does not bypass DRM or platform restrictions. Direct media downloads may be limited by CORS and host settings.
