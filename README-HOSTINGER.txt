DAMASCUS VILLAGE WEBSITE - Production-ready package (GitHub / Hostinger)
==========================================================================

CONTENTS (all at root level - nothing nested in a subfolder)
- index.html ............ the complete website (all CSS & JS linked,
                          Google Fonts via CDN)
- icon.jpg .............. site icon
- images/ ............... every static asset with relative paths
  - images/dishes/ ...... 28 real dish photos (menu + ordering)
  - images/heritage/ .... 3 Damascus heritage photos (4K)
  - images/breakfast-4k/  4 breakfast photos (4K)
  - images/location-video-5s.mp4 ... 5s drone video (location section)
  - images/location-video-poster.jpg  video poster frame
  - images/hero-damascus-village.jpg  hero background
  - images/hatch-maps.js / .css, map_helpers.js ... map components

HOW TO IMPORT TO HOSTINGER
Option A - hPanel File Manager:
1. Log in to Hostinger hPanel > File Manager.
2. Open public_html (or your domain's folder).
3. Upload this ZIP > right-click > Extract.
4. index.html must sit directly inside public_html.
5. Open your domain - the site is live.

Option B - GitHub Pages:
1. New repo > upload these files to the repo root.
2. Settings > Pages > Deploy from branch (main, /root).
3. Live at username.github.io/repo-name.

NOTES
- 100% static: no database/PHP needed, works on any hosting plan.
- Table reservations confirm on-screen with call/email handoff
  (confirmed by phone, not stored on a server). For live online
  booking later, connect OpenTable/Resy to the Reserve buttons.
- The Order section builds the order and hands it off via phone/email.
