# RON EZEKIEL STUDIO PRO

Elegant, responsive music-channel CRM starter for GitHub Pages.

## Features
- Overview with local content pipeline charts
- Video manager: create, edit, search, filter, delete
- Music library: track asset names and HTTPS links
- Monthly content calendar based on video dates
- Copyright claim notes
- Export/import JSON backup
- Browser localStorage persistence

## Deploy on GitHub Pages
1. Create a public GitHub repository named `ron-ezekiel-studio`.
2. Upload `index.html` to the root of the repository.
3. Open **Settings → Pages → Build and deployment**.
4. Select **Deploy from a branch**, branch **main**, folder **/(root)** and save.
5. Wait for deployment and open the Pages URL shown by GitHub.

## Important limitations
This is a static, local-first CRM, not an official YouTube Studio client. Sample records are examples and the charts show your saved production stages, not YouTube analytics. Data is stored in localStorage on each browser/device and does not sync. Export JSON backups regularly. Large audio/video files are not stored in the CRM. Public channel stats could be integrated with YouTube Data API later; private analytics and publishing require OAuth and a secure backend. Do not commit API secrets or OAuth tokens to a public repository.

External dependencies: Google Fonts and Chart.js CDN (charts require internet access).
