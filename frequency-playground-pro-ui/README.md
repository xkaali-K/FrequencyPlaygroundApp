# Frequency Playground — Pro UI Landing Page

This package contains the **full professional UI** landing page (glassmorphism + cosmic gradients) and the media gallery hook.

## Add your media
1. Put images in `/images/` and videos in `/videos/`.
2. Open `index.html` and scroll to the bottom. Find the `MEDIA` array:
```js
const MEDIA = [
  // { type: 'image', src: 'images/screenshot-1.png', alt: 'Sacred Geometry Viewer' },
  // { type: 'video', src: 'videos/demo.mp4', poster: 'images/poster.jpg', alt: 'Demo video' },
];
```
3. Replace with your files, e.g.:
```js
const MEDIA = [
  { type: 'image', src: 'images/Screenshot-2025-08-27-004324.png', alt: 'Sacred Geometry Viewer' },
  { type: 'image', src: 'images/Screenshot-2025-08-27-004412.png', alt: 'Combined Sine Waves' },
  { type: 'image', src: 'images/Screenshot-2025-08-27-004510.png', alt: 'Waveform Animation' },
  { type: 'image', src: 'images/Screenshot-2025-08-27-004533.png', alt: 'Binaural Beats Visualization' },
];
```

## Deploy
- Upload these files to your GitHub repo root.
- Enable GitHub Pages: Settings → Pages → Branch: `main`, Folder: `/ (root)`.
- Your site: `https://YOUR-USERNAME.github.io/REPO-NAME/`
