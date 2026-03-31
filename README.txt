═══════════════════════════════════════════════════════════
  KHETHO MNGOMEZULU — MARCH 2026 KPI PRESENTATION
  Brandscapers Africa
═══════════════════════════════════════════════════════════

HOW TO USE
──────────
1. Open index.html in any modern browser (Chrome recommended)
2. Click anywhere or wait 8 seconds to enter the presentation
3. Navigate with arrow keys or the on-screen buttons

FOLDER STRUCTURE
────────────────
kpi-presentation/
│
├── index.html              ← The presentation (open this)
├── README.txt              ← This file
│
├── your-photo.jpg          ← YOUR PORTRAIT (rename & place here)
│
├── screenshots/            ← SLIDE 4 — 27 website screenshots
│   ├── website-01.jpg
│   ├── website-02.jpg
│   ├── website-03.jpg
│   │   ... up to ...
│   ├── website-27.jpg
│   ├── 3k-autobody.jpg     ← Slide 8 (Pro Bono)
│   └── ens-foundation.jpg  ← Slide 9 (ENS Foundation)
│
├── logos/                  ← SLIDE 5 — 20 logo designs
│   ├── logo-01.png
│   ├── logo-02.png
│   │   ... up to ...
│   └── logo-20.png
│
├── bidvest/                ← SLIDE 6 — 3 Bidvest screenshots
│   ├── bidvest-01.jpg
│   ├── bidvest-02.jpg
│   └── bidvest-03.jpg
│
└── pitches/                ← SLIDE 14 — 3 WhatsApp pitch screenshots
    ├── pitch-01.jpg
    ├── pitch-02.jpg
    └── pitch-03.jpg


HOW TO CHANGE IMAGE PATHS
──────────────────────────
Open index.html in a text editor (Notepad, VS Code, etc.)

Search for:   const WEBSITES = [
You will find 27 entries like this:
  { label: 'Website 01', img: './screenshots/website-01.jpg', url: 'https://website01.co.za' },

Change:
  label  → The actual client/site name (shows on hover & lightbox)
  img    → Path to your screenshot file
  url    → The actual live URL (opens when "Check Me Out" is clicked)

Example:
  { label: 'Sekatebo', img: './screenshots/sekatebo.jpg', url: 'https://sekatebo.co.za' },


Search for:   const LOGOS = [
You will find 20 entries like this:
  { label: 'Logo 01', img: './logos/logo-01.png' },

Change:
  label  → The brand name
  img    → Path to your logo file (PNG, JPG or SVG all work)


YOUR PORTRAIT
─────────────
Search the file for:   ./your-photo.jpg
It appears 4 times:
  1. Intro screen (full-bleed background)
  2. Hero slide (left column, large)
  3. Top-left HUD avatar (small circle)
  4. Closing slide (spinning ring)

Simply rename your photo file to  your-photo.jpg
and place it in the same folder as index.html.

OR search & replace  ./your-photo.jpg  with your actual filename.


TIPS
────
• Use JPG for screenshots (smaller file size, faster loading)
• Use PNG for logos (preserves transparency)
• Recommended screenshot size: 1280×800px or larger
• Recommended logo size: 400×400px minimum
• If an image is missing, a placeholder loads automatically
• The presentation works offline — no internet needed
  (except for Google Fonts on first load)


NAVIGATION
──────────
• Arrow keys ← → to move between slides
• Click the nav buttons (bottom right)
• Click the dots (bottom centre) to jump to any slide
• Swipe left/right on touch devices
• Press Escape to close the lightbox


═══════════════════════════════════════════════════════════
