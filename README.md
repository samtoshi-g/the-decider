# The Decider

**Psychology-based decision helper using A/B matchups + reaction time weighting**

## What It Does
Enter 2-6 options you're deciding between. The app pits them against each other in rapid-fire head-to-head matchups. Faster reactions = stronger preference signal.

## Demo
Single-file PWA. Just open `index.html` in a browser.

## Deploy

### Vercel (recommended)
```bash
cd projects/the-decider
vercel deploy --prod
```

### Netlify
Drag and drop the folder to netlify.com/drop

### Manual
Upload `index.html` and `manifest.json` to any static host.

## Tech
- Pure HTML/CSS/JS
- No build step
- PWA-ready (installable)
- ~27KB total

## Features
- 2-6 option comparisons
- Reaction time weighted scoring
- Confidence calculation
- Full rankings
- Share results
- Keyboard shortcuts (1/2, arrows)
- Mobile-friendly

## Analytics (TODO)
Add Plausible or Fathom before launch for tracking.

---
Built by Sam for Eric's consulting portfolio.
