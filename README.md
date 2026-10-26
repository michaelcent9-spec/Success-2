# Operation: Success

A cinematic, mobile-friendly encouragement website for a Grade 6 CBC learner in Kenya. Built with HTML5, CSS3, and vanilla JavaScript. No build step, backend, API key, or paid hosting is required.

## Files
- `index.html` — all page sections and content
- `css/style.css` — responsive design, colours, layout, animations, reduced-motion support
- `js/main.js` — navigation menu, local checklist, focus timer, optional generated tones
- `assets/images/` — 14 WebP images supplied by the project owner

## Run locally
Open `index.html` in a modern browser. For local testing, a simple static server is optional. All file paths are relative and suitable for a GitHub Pages project site.

## Deploy on GitHub Pages
1. Create a new repository (for example, `Success-123`).
2. Upload the **contents of this folder**, not the ZIP file and not the enclosing folder. `index.html` must be at the repository root.
3. Confirm that `css/style.css`, `js/main.js`, and `assets/images/` are present with the exact names and capitalisation shown.
4. Open **Settings → Pages**.
5. Under build and deployment, select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
6. Wait for deployment and open the URL displayed in Settings → Pages.

## Features
- Responsive layout for mobile, tablet, and desktop
- Accessible skip link, keyboard focus styles, labelled controls, and reduced-motion support
- Exam strategy panel
- Checklist progress saved in browser local storage; reset button clears it on the current device
- 25-minute timer with start, pause, resume, reset, and optional sound effects (off by default)
- User-supplied TikTok link opens externally; no autoplay and no video is hosted by this project

## Image and video notes
The 14 supplied PDF images are included as local WebP files. The original creator and reuse licence were not independently verified. See `ATTRIBUTION.md` before making the site public. The TikTok link is supplied by the project owner and is not guaranteed to remain available or permit embedding.

## Limitations
- No live GitHub Pages deployment can be verified from the source package alone.
- Fonts are loaded from Google Fonts when internet access is available; system font fallbacks are provided.
- This is an unofficial fan-inspired project and is not affiliated with anime studios or rights holders.
