# SPINS-Hydro updated website

Updated multi-page website for the SPINS-Hydro V2P2 project.

## Copyright and use

© SPINS-Hydro Project Team. All rights reserved.

The text, images, figures, design content, and project materials in this repository and website are provided for viewing only. They may not be copied, shared, reproduced, modified, redistributed, or republished without prior written permission from the SPINS-Hydro Project Team.

## Website pages

- `index.html` — compact project overview and main navigation portal
- `sub-projects.html` — gateway to the three detailed research pages
- `researchers.html` — researcher group and collaborating organisations
- `news.html` — project news and research updates
- `contact.html` — project contact information
- `mangrove-planter.html` — mangrove and concrete planter research
- `seagrass-perched-beach.html` — seagrass and perched beach research
- `seagrass-geomorphology.html` — real seagrass and bed geomorphology research
- `assets/styles.css` — shared responsive design
- `assets/site.js` — mobile navigation, section highlighting and reveal effects
- `assets/` — project photographs and visual materials

## How to view
Open `index.html` in a browser. For local development, you can also run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## How to edit

Homepage content is in `index.html`. Each sub-project has its own HTML file, while styling and navigation behaviour are shared through the `assets` folder.
