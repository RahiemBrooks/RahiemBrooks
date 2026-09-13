# Rahiem J. Brooks — Research Portfolio

A single-page research portfolio covering cross-cultural measurement of
caregiving, instrument validation, and family-facing intervention design.

**Live site:** https://RahiemBrooks.github.io

## About

I study how caregiving gets measured, and what follows for the tools we
build for families. The site is organized around that question: a
research program in three strands, the projects that make it concrete,
publications and preregistrations, presentations, and selected academic
writing.

## Built with

Static HTML, CSS, and vanilla JavaScript. No framework, no build step,
no dependencies. Typography is Inter and Playfair Display via Google
Fonts. Deployed on GitHub Pages.

Interactive elements are hand-rolled: responsive navigation with a
mobile menu, scroll-linked active section highlighting, an
IntersectionObserver for reveal-on-scroll, a lightbox for the research
posters, and smooth anchor scrolling with navbar offset.

## Structure

```
.
├── index.html              # the site
├── css/style.css           # design tokens and all styling
├── js/main.js              # navigation, scroll effects, lightbox
├── assets/images/          # portrait, posters, project images
├── papers/                 # coursework and poster PDFs
├── Rahiem_Brooks_CV.pdf    # curriculum vitae
└── Rahiem_Brooks_CV.docx   # editable source
```

## Running locally

No build required. Open `index.html` in a browser, or serve the
directory:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Pushed to the `main` branch and published from the root via GitHub
Pages (Settings → Pages → Deploy from a branch → `main` / `/ (root)`).

## Elsewhere

- ORCID — https://orcid.org/0009-0000-5095-2200
- OSF — https://osf.io/hpuf9/
- LinkedIn — https://linkedin.com/in/rahiembrooks
- PANDA Study — https://www.thepandastudy.com

## Contact

brooksrahiem@gmail.com · Chapel Hill, North Carolina

---

© 2026 Rahiem J. Brooks. Content and writing are all rights reserved;
the site code may be reused with attribution.
