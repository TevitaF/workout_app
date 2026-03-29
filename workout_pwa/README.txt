# Workout Tracker PWA

Files:
- index.html
- manifest.webmanifest
- service-worker.js
- icons/

## Easiest way to use it
Upload this whole folder to one of these:
- Netlify
- Vercel
- GitHub Pages

It must be served over HTTPS for install + offline features.

## Install on phone
### iPhone
Open in Safari -> Share -> Add to Home Screen

### Android
Open in Chrome -> Install App / Add to Home Screen

## Update note
If you make major changes later, bump the CACHE_NAME in service-worker.js
so phones pull the newest version cleanly.
