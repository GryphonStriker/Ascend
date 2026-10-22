ASCEND v0.6.2 — Installable PWA

DEPLOY
1. Upload the CONTENTS of this folder (index.html, manifest.webmanifest, service-worker.js and icons/) to an HTTPS static host, such as GitHub Pages or Cloudflare Pages. Keep the file structure intact.
2. Open the hosted URL in Safari on your iPhone. Use Share > Add to Home Screen and enable Open as Web App if offered.
3. Launch Ascend from the new icon. Open it online once before relying on offline mode.
4. On each device, use History & Saves > Export / Import to transfer progress if needed.

NOTES
- Opening index.html as a local file does not enable installation or service-worker offline caching.
- Save data stays in that browser / installed app's localStorage; it is not sent to the hosting provider and does not automatically sync.
- Safari and the installed Home Screen app may have separate storage. Export your existing save before switching.
- Clearing app/site data or uninstalling the app can remove progress; export regular backups.
- Updates may require closing and reopening the app or revisiting while online.
- App files on a public static host are public. Do not put personal data or passwords in these files.
- Existing Ascend save key and XP rules are unchanged.
