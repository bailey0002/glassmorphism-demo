
Concordïa • Glassmorphism Sidebar (icon-free) — v1

Preview on GitHub Pages
-----------------------
1) Create a PUBLIC repo (e.g., concordia-sidebar-glass).
2) Upload index.html and the /assets folder.
3) Settings → Pages → Deploy from a branch → main /(root).
4) Open https://<your-username>.github.io/<repo-name>/

Add your shimmer video
----------------------
- Export a 2–4 second loop, muted, 24 fps, ≤ 1.5 MB.
- Provide both files if possible:
    assets/concordia_shimmer.mp4
    assets/concordia_shimmer.webm
- If no video is present, a CSS shimmer runs automatically.

Swap logos
----------
- Dark UI:  assets/concordia_logo_light.png  (white/ice on transparent)
- Light UI: assets/concordia_logo_dark.png   (charcoal/black on transparent)
- Suggested width: 560–720 px (2×), sRGB.

Use in Word add-in
------------------
- Copy the header/card markup and CSS into your taskpane.
- Keep width near 375–420 px and blur at 16–20 px.
- Video is optional and respects reduced-motion preferences.
