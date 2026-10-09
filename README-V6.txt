STARE FEDRE FINANCE V6.0

Files to upload/replace on GitHub Pages:
- index.html
- sw.js
- manifest.webmanifest

Keep your existing:
- app-config.js
- icon-192.png
- icon-512.png

Add this property inside window.STARE_FEDRE_CONFIG in app-config.js:
  adminPin: 'YOUR_PRIVATE_PIN',

Example is included in app-config.example.js.

Viewer mode is the default. Admin mode lasts only for the current browser session.
Important: this is a UI access layer. Because GitHub Pages is a static public site,
a technically skilled viewer can inspect client-side code. Strong security requires
server-side authorization in Google Apps Script for every save/change request.
