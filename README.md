# YouthWave MY

> **Pertubuhan Gelombang Muda Malaysia** is a Malaysian youth NGO representing the
> voices of young people on current national issues.

Part of [Build for Public](https://buildforpublic.com), open tech for the public good.

---

## Status: v1 Built!

The initial landing page has been built. It uses vanilla HTML/CSS/JS with no build step.

## Repository Structure

```text
youthwave/
├── index.html        # Main landing page (HTML/JS)
├── style.css         # Styling and layout
├── images/           # Visual assets
│   ├── logo.png      # Organization logo
│   ├── event.png     # Background imagery
│   └── posts/        # Lightbox post images
├── README.md         # Project documentation (this file)
└── .gitignore        # Git ignore rules
```

## Local Preview

1. **Quick View:** Double-click `index.html` to open in your browser.
2. **VS Code:** Install "Live Server" extension, right-click `index.html` → "Open with Live Server" (recommended for hot reload).
3. **Python Server:** Run `python -m http.server` in terminal, then open `http://localhost:8000`.



Keep it **open and built in public**: free, open-source, built together.

## Find them

- **Facebook:** https://www.facebook.com/youthwaveMY/
- **LinkedIn:** https://my.linkedin.com/company/pertubuhan-gelombang-muda-malaysia-youthwave

## Contribute

This repo is the home for whatever gets built. Once the scope is agreed, drop a
short brief here (problem, who it helps, the pages/features) so others can join.
Open a PR or an issue to get started.

---

## Next Steps & Open Questions

Questions to clarify with YouthWave before finalizing the website:

### 1. Impact Stats for the Website
- [ ] **Status:** ⏳ Waiting on YouthWave

The stats strip below the hero currently shows vanity metrics (Instagram followers, posts shared, etc.) that don't communicate real NGO impact. We need **3–4 meaningful numbers** to replace them.

**Action needed:** Provide 3–4 real stats with approximate figures (e.g., "100+ Volunteers", "15+ Communities", "50+ Events").

### 2. High-Resolution Logo
- [ ] **Status:** ⏳ Waiting on YouthWave

The current logo (`images/logo.png`) works well against the background, but an **SVG or high-res PNG** (ideally with transparent background) would look much sharper on all screen sizes.

**Action needed:** Provide an SVG or large PNG (1000px+ wide) of the PGMM / YouthWave logo.

### 3. Maybank Donation Account: Still Active?
- [ ] **Status:** ⏳ Waiting on YouthWave

The site shows account number `514123692964` under "Pertubuhan Gelombang Muda Malaysia" with a copy-to-clipboard button. Need to confirm:
- Is this account still active for donations?
- Is the registered name correct?
- Any other payment methods to add?

### 4. Contact Info Accuracy
- [ ] **Status:** ⏳ Waiting on YouthWave

Currently displayed on the site:
- **WhatsApp:** +60 14-759 2903
- **Email:** youthwaveofficial@gmail.com
- **Location:** Kuala Lumpur, Malaysia

**Action needed:** Confirm these are current and correct.

### 5. Event Photos & Content
- [ ] **Status:** ⏳ Waiting on YouthWave

The site uses photos from Facebook posts. Questions:
- Are these the right photos to showcase?
- Do you have higher-resolution versions?
- Any new events or programs to feature?
- Are the captions and descriptions accurate?

### 6. HQ Location Coordinates
- [ ] **Status:** ⏳ Waiting on YouthWave

The map marker and "Get Directions" link were updated to point to coordinates `3.151696, 101.694237` (retrieved from LinkedIn).

**Action needed:** Confirm if this is the exact correct HQ location for YouthWaveMY.

---

## Future Improvement Plans
**Status:** ⏳ Open for Discussion

Collaborator suggestions to consider for upcoming iterations:

- **Main Hero Photo:** Should the main photo be replaced? A banner might not instill as much confidence. Perhaps using high-quality photos from actual events would build more trust.
- **Donation Friction:** Include a QR code (e.g., DuitNow/bank QR) for donations. This makes the process much easier and reduces friction for users wanting to contribute.
- **Hosting / Deployment:** How should we approach hosting and deployment? We need to finalize where to host the site (e.g. GitHub Pages, Vercel, Netlify) and what domain to use for the live launch.
- **Recruitment Form/Page:** Create a dedicated form or landing page to streamline the recruitment process for new volunteers and members.
- **Dynamic Carousel:** Automate carousel to fetch latest Facebook/Instagram posts automatically instead of manual updates.
