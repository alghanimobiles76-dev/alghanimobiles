AL GHANI MOBILES — INSTALLABLE IPHONE WEB APP

IMPORTANT:
This is a Progressive Web App (PWA) package. iPhone installation requires it to be hosted on an HTTPS website.
Opening index.html directly from the Files app will NOT install it and will not enable service-worker offline caching.

FILES:
- index.html: app
- manifest.webmanifest: install metadata
- sw.js: offline cache
- icons/: home-screen icons

DEPLOY:
Upload the CONTENTS of this folder to an HTTPS static hosting service (for example, a static site host).
Then open the HTTPS URL in Safari on iPhone:
1. Tap Share.
2. Choose Add to Home Screen.
3. Enable Open as Web App if shown.
4. Tap Add.

Open the installed home-screen icon once while online. After the first successful load, the app shell can open offline.
Data is stored locally on each device; this package does NOT sync employee phones together.
Use the app's Backup page to export/import JSON backups.
