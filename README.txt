SATHISH KUMAR — INTERACTIVE LUXURY PORTFOLIO

Includes: cinematic intro, black/cream/champagne-gold theme, mouse portrait tilt, cursor glow, cursor-following eye overlay, optional video background, scroll reveal, animated project cards, category filters, mobile menu and responsive layout. No paid app or build tools required.

PREVIEW
1. Extract this ZIP.
2. Open index.html in a modern browser.
3. For optional video and best testing, open a terminal in this folder and run: python -m http.server 8000; then visit http://localhost:8000.

YOUR PORTRAIT
assets/portrait.png is included as a starting portrait from your available portfolio images. To use your exact preferred original photo, replace it but keep the same filename.

VIDEO BACKGROUND
Add a compressed MP4 named assets/hero.mp4. Use muted footage you own or have permission to use. Without the file, the dark cinematic gradient remains as fallback.

EYE TRACKING POSITION
In styles.css, adjust --eye-y, --eye-left, and --eye-right percentages. This overlay is a stylized demo and may need alignment for your specific photo. For a forward-facing portrait, start with --eye-y:31%; --eye-left:39%; --eye-right:58%. Hide .eye-tracker if it doesn't align naturally.

CUSTOMIZE
Change hello@example.com in index.html to your actual email. Replace sample project cards and descriptive text with your real projects and links.

GITHUB PAGES
Upload index.html, styles.css, script.js and the full assets folder to the repository root. Go to Settings > Pages, select deploy from main branch and /(root), then save.

This is a static front-end portfolio. It has no backend/contact form submission. Google Fonts requires internet; fallback fonts work offline.
