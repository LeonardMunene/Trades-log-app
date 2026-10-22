TRADING JOURNAL - installable app (PWA)

Contents: index.html, manifest.webmanifest, sw.js, icons/

1) Put it online (free, ~1 minute)
   Netlify: go to app.netlify.com/drop, unzip this folder, drag the folder in.
   Or GitHub Pages / Cloudflare Pages: upload all files, keep the folder structure.
   It must be served over https for install + offline to work.

2) Install on your phone
   iPhone (Safari): open your link > Share > Add to Home Screen.
   Android (Chrome): open your link > menu > Install app / Add to Home screen.

Notes
- Trades are saved on the phone (browser storage) and the app works offline. Use Tools > Backup regularly.
- Data stays on that device/browser; it does not sync with the claude.ai version.
- To update the app later, change the files and bump CACHE in sw.js (v1 -> v2).
