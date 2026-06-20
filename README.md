# parkerdifuntorum.com

Polished static personal website for Parker Difuntorum, M.S., E.I.T.

## Files
- `index.html`
- `styles.css`
- `script.js`
- `README.md`

## Included updates
- Name is the largest hero text
- Credentials added next to name area: `M.S. | E.I.T. | U.S. Coast Guard Veteran`
- Keeps tagline: "Power systems engineer building practical bridges between grid operations, planning, data, research, and resilient automation."
- Adds affiliation/logo placeholders for USCG, CSU Sacramento, and UF
- Adds metrics row: publications, patent applications, experience, Power + AI research
- Adds expanded experience timeline:
  - Liberty Utilities
  - PG&E
  - University of Florida Research
  - Ulteig
  - Delta Wireless
  - Intel
  - U.S. Coast Guard
- Adds education section
- Adds project cards
- Adds publication and patent links
- Uses exact links:
  - Google Scholar: https://scholar.google.com/citations?user=g2ff33cAAAAJ&hl=en
  - LinkedIn: https://www.linkedin.com/in/parker-difuntorum-89703519b/
  - TPL Studies Web App: https://transmissionstudies.streamlit.app/

## Logo note
The current version uses clean text-based logo/emblem placeholders to avoid bundling trademarked or copyrighted image files.
To use official images, replace the `.logo-badge` blocks in `index.html` with image tags, for example:

```html
<img src="assets/uscg-seal.png" alt="U.S. Coast Guard seal">
<img src="assets/csu-sacramento-logo.png" alt="California State University, Sacramento logo">
<img src="assets/uf-logo.png" alt="University of Florida logo">
```

Then place the image files inside an `assets/` folder.

## Deploy on Vercel
1. Create or open a GitHub repo named `parkerdifuntorum.com`.
2. Upload these files to the root of the repo.
3. Import the repo into Vercel.
4. Add `parkerdifuntorum.com` and `www.parkerdifuntorum.com` under Project Settings > Domains.
