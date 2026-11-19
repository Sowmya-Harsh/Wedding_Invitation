# #RoRo — Rohith & Roja wedding website

A lightweight, responsive static website made for GitHub Pages. No build step or framework required.

## Preview locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a GitHub repository (for example, `roro-wedding`).
2. Upload the contents of this folder — keep `index.html`, `styles.css`, `script.js`, and `assets/` together.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. GitHub will provide your public website URL after deployment.

## Personalise before publishing
- **Photo upload link:** Open `script.js` and replace the empty value in `const UPLOAD_URL = "";` with your shared Google Drive folder link or upload destination. The upload button and QR code will then become active. The QR image is generated using QR Server when the page is viewed.
- **Venue and time:** Edit the “Exact ceremony time…” and “Venue details coming soon” text in `index.html` when you have the confirmed details.
- **Gallery art:** The site is illustration-first and uses the custom watercolor-style couple artwork plus the rose-over-R emblem extracted from the engagement backdrop. No real engagement photo is displayed.
- **Photos:** Replace `assets/engagement.jpg` with your preferred hero/gallery photo (keep the same filename, or update the image paths in `index.html`).

## Current content notes
The site uses the confirmed names Rohith & Roja and date Saturday, 19 December 2026. The venue is Kottaya Convention Hall, RTO Office Road, Kakinada, Andhra Pradesh, India. The invitation indicates 7:00 PM on Saturday, 19 December 2026. The wedding and reception are both included; separate reception timing has not been supplied and is left as a placeholder. RSVP destination and photo upload destination remain placeholders until supplied.
