IAI Prototype v0.2 — PWA-ready package

This version includes:
- Responsive English/Amharic website prototype
- Crescent SVG app icon
- Web app manifest
- Service worker for caching/offline shell after first successful visit

IMPORTANT:
- This is still a front-end prototype. No real AI model, accounts, payments, database,
  or server connection is included.
- The chat is a demo only; it does not send questions to a server.
- Installability and offline caching require the files to be hosted over HTTPS
  (localhost is also allowed for development). Opening index.html directly from
  Downloads will show the page but will not enable PWA installation/service workers.
- Hosting free tiers and terms can change. No paid service is required to test locally.
- Never place secret API keys in HTML or browser JavaScript.
