# maheshPM

Portfolio site for **H. Mahesh**: programme and project delivery for enterprise applications in financial services and government.

Static site (HTML, CSS, vanilla JavaScript). No build step, framework or backend.

**Intentionally excluded:** resume PDF, resume links, and GitHub profile links.

## Files

```text
maheshPM/
├── index.html          # Portfolio content
├── assets/
│   ├── css/style.css   # Design and responsive layout
│   └── js/main.js      # Mobile menu, active-section highlight, reveal effects
├── .nojekyll
└── README.md
```

## Run locally

```bash
python -m http.server 8000   # then open http://localhost:8000
```

## Publish with GitHub Pages

1. On GitHub, click **+ → New repository**, name it `maheshPM`, set it to **Public**, and create it.
2. Click **uploading an existing file** and drag in the *contents* of this folder (`index.html` must be at the root). Commit to `main`.
3. **Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.**
4. After 1–2 minutes the site is live at **https://mahitechnical.github.io/maheshPM/**.

## Content rules

Every title, date and figure on the site comes from the current resume. SIT/UAT and SOW and commercial delivery were added as skills at the owner's confirmation; add them to the CV too so the two match. Do not add platforms or experience (for example Kyriba, ERP or CRM) until the resume states them. Summaries are high-level; no confidential employer code, data or architecture is published.
