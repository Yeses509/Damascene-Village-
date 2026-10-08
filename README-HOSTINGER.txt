DAMASCUS VILLAGE WEBSITE - Production-ready package (GitHub / Hostinger)
==========================================================================

CONTENTS (all at root level - nothing nested in a subfolder)
- index.html ............ the complete website (all CSS & JS linked)
- images/ ............... every static asset, clean sequential names
  - images/img-01.jpg ... images/img-41.jpg ... all photos
      (dishes, heritage 4K, breakfast 4K, hero, site icon)
  - images/hero-video.mp4 ... 5s drone video (location section)
  - images/hero-poster.jpg . video poster frame
  - images/hatch-maps.js / .css, map_helpers.js ... map components

FILE NAMING
All files are lowercase with simple sequential names (img-01.jpg ...)
to avoid any pathing, case-sensitivity or filename mismatch issues
on production hosting. Every reference in index.html points to
images/ with the exact new names.

HOW TO IMPORT TO HOSTINGER
1. hPanel > File Manager > open public_html.
2. Upload this ZIP > right-click > Extract.
3. index.html must sit directly inside public_html.
4. Open your domain - the site is live.

GitHub Pages: upload these files to the repo root >
Settings > Pages > Deploy from branch (main, /root).

NOTES
- 100% static: no database/PHP needed, works on any hosting plan.
- Table reservations confirm on-screen with call/email handoff
  (confirmed by phone, not stored on a server).
