# Frequency Playground Website

## File structure
- index.html : main landing page
- /images/   : put your screenshots, logos, and GIFs here
- /videos/   : put your demo .mp4 or .webm files here

## How to add media
Edit the index.html file and update the MEDIA array in the <script> block:
```js
const MEDIA = [
  { type: 'image', src: 'images/your-image.png', alt: 'Description' },
  { type: 'video', src: 'videos/your-video.mp4', alt: 'Demo video' },
];
```
