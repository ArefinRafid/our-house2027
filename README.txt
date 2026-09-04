OUR HOUSE — FINAL iPad PWA

Firebase sync is configured for project: our-house-fc269.

GitHub:
1. Replace the existing files in your our-house repository with ALL files from this folder.
2. Keep index.html, manifest.webmanifest, sw.js and both icons in the repository root.
3. Wait for GitHub Pages to deploy.
4. On each of the 6 devices open the same URL.
5. Settings -> 6-phone Sync -> enter the same House Code -> Connect / Sync.

IMPORTANT:
- This app works offline and stores data locally.
- Firebase sync requires internet.
- Anonymous Authentication must be enabled (you already enabled it).
- Realtime Database must exist.
- Database rules should be configured to allow authenticated users; do not leave an open public database in production.
- Local PIN locks only the current device.
