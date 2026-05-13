# V2P2_hybrid
website design for v2p2 project

## Copyright and use

© SPINS-Hydro Project Team. All rights reserved.

The text, images, figures, design content, and project materials in this repository and website are provided for viewing only. They may not be copied, shared, reproduced, modified, redistributed, or republished without prior written permission from the SPINS-Hydro Project Team.

## Files
- `index.html` — main website page
- `assets/styles.css` — responsive styling
- `assets/site.js` — navigation highlighting and progress animation
- `assets/` images — project visuals used in the public website. This version excludes the wave-distribution figure and equation display.

## How to view
Open `index.html` in a browser. For local development, you can also run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## How to edit
All content is in `index.html`. Milestone percentages are controlled by `style="--p: XX%"` on each `.progress-card`.
