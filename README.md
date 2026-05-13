# arche-landing

Single-page landing site for **Arche Industries**, plus a `/manifesto` page.
Pure static HTML/CSS/JS — no build step, no framework.

```
.
├── index.html              # landing page (rotating ASCII cube)
└── manifesto/
    ├── index.html          # essay + stacked staggered figure gallery
    └── images/             # cropped figures + founder portraits
```

## Run locally

```bash
python3 -m http.server 8765
# open http://localhost:8765/
```

## Deploy

Any static host works — drop the repo root into Render Static, Vercel,
Netlify, GitHub Pages, S3, etc. There is nothing to build.
