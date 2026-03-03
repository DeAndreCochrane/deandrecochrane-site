# DeAndre R. Cochrane — Personal Website Project
**Live Site:** https://deandrecochrane.com  
**Hosted on:** Bolt.new  
**Domain:** Registered via Netlify → connected to Bolt  
**Last Updated:** March 2026

---

## Folder Structure

```
deandrecochrane-site/
│
├── source/
│   └── index.html          ← LIVE VERSION (v6) — deploy this file
│
├── versions/
│   ├── deandre-cochrane.html     ← v1 (initial concept)
│   ├── deandre-cochrane-v2.html  ← v2 (AI narrative added)
│   ├── deandre-cochrane-v3.html  ← v3 (accurate LinkedIn data, real certs, emails)
│   ├── deandre-cochrane-v4.html  ← v4 (FY26 performance dashboard added)
│   ├── deandre-cochrane-v5.html  ← v5 (performance reframed, font fixes)
│   └── deandre-cochrane-v6.html  ← v6 (all Syne → Cormorant Garamond swap)
│
├── assets/
│   ├── IMG_7729.png        ← LinkedIn experience screenshots
│   ├── IMG_7730.png
│   ├── IMG_7731.jpeg
│   └── IMG_7732.png
│
├── reference-screenshots/
│   ├── linkedin-8_26.41 PM.png   ← LinkedIn certifications (screens 1-6)
│   ├── linkedin-8_26.44 PM.png
│   ├── linkedin-8_26.47 PM.png
│   ├── linkedin-8_26.50 PM.png
│   ├── linkedin-8_26.54 PM.png
│   ├── linkedin-8_26.56 PM.png
│   ├── site-preview-contact.png  ← Site design reference screenshots
│   ├── site-preview-beyond-role.png
│   └── bolt-dashboard.png        ← Bolt.new hosting dashboard
│
└── README.md               ← This file
```

---

## Tech Stack

- **Pure HTML/CSS/JavaScript** — single file, no frameworks, no dependencies
- **Fonts (Google Fonts CDN):**
  - Cormorant Garamond — all headings, labels, UI text, all-caps elements
  - Syne — body text, navigation body
  - DM Mono — dates, technical metadata, monospace data
- **Canvas API** — animated particle network background
- **IntersectionObserver API** — scroll-triggered reveal animations

---

## Key Sections

| Section | Description |
|---|---|
| Hero | Name, title, animated entrance, CTAs |
| Ticker | Scrolling keyword bar |
| AI Narrative | Three pillar cards — Copilot, Azure Infrastructure, IP Co-Sell |
| Stats Strip | 17 certs, 5+ yrs, Guinness Record, 3 kids |
| FY26 Performance | Tabbed dashboard — Q1/Q2/Q3/Q4 quota attainment |
| Certifications | All 17 Microsoft credentials organized by category |
| Expertise | 4 skill cards |
| Career Timeline | Full progression from Northwestern Mutual → Microsoft |
| Education | Augusta University + Albany State University |
| Philosophy | Quote + values |
| Contact | LinkedIn, work email, personal email, location |
| Beyond the Role | CBMC, Cochrane & Co, Devoted Church, Family |

---

## Contact Info on Site

- **Work:** dcochrane@microsoft.com
- **Personal:** cochrane.deandre12@gmail.com
- **LinkedIn:** linkedin.com/in/deandrecochrane
- **Location:** Atlanta Metro · McDonough, GA

---

## Performance Data (FY26 — Attainment % Only)

| Workload | Q1 | Q2 | Q3 | Q4 |
|---|---|---|---|---|
| Migrate & Modernize | 125% | 110% | In Progress | Pipeline |
| Data Analytics | 145% | 132% | 85% (mid-Q) | Pipeline |
| AI Platform & Apps | 103% | 94% | 32% (mid-Q) | Pipeline |
| Defender for Cloud | 164% | 65% | TBD | Pipeline |

*Q3 in progress as of March 2026. Q4 not yet open.*

---

## To Update the Site

1. Open `source/index.html` in any code editor
2. Make your changes
3. Upload/deploy the updated file to Bolt.new (or any host)
4. Save a copy in `versions/` with the next version number

## To Deploy Elsewhere

The entire site is **one self-contained HTML file** — `source/index.html`.  
Drop it anywhere that serves static HTML:
- **Bolt.new** (current)
- **Netlify** — drag and drop
- **Vercel** — drag and drop
- **GitHub Pages** — push to repo
- **Cloudflare Pages** — connect repo or drag and drop
