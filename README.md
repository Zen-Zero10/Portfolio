# Soumyajit Das — Portfolio

A single-file portfolio site styled as an airport departures board crossed with a
terminal — built to showcase AI/ML and cybersecurity work for internship and job
applications.

**Live site:** _add your GitHub Pages URL here once deployed, e.g._
`https://zen-zero10.github.io/portfolio/`

---

## About

This repo holds my personal portfolio: a bio, my two internships (AI/ML and
Cybersecurity), my Flight Price Prediction project, skills, education, and contact
details — all in one static page, no build step required.

## Tech

- HTML, CSS, vanilla JavaScript — no framework, no build tools
- Google Fonts: Space Grotesk (display), JetBrains Mono (labels/data), Inter (body)
- Hosted free on GitHub Pages

## Structure

```
.
├── index.html      # the entire site (markup + styles + script, self-contained)
├── resume.pdf       # downloadable résumé, linked from the site
└── README.md
```

## Run locally

No build step needed — just open the file:

```bash
git clone https://github.com/Zen-Zero10/<this-repo>.git
cd <this-repo>
open index.html   # or double-click it, or use a local server:
python3 -m http.server 8000
```

## Deploy on GitHub Pages

1. Push `index.html` and `resume.pdf` to this repo's `main` branch (already done if
   you're reading this here).
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch** → branch `main`, folder `/root`.
   Save.
4. Wait a minute or two, then open the URL shown on that same Pages settings screen.
5. Come back and drop that URL into the "Live site" line at the top of this README.

## Customizing

- All content lives directly in `index.html` — no CMS, no data files. Search for the
  section you want (`id="work"`, `id="projects"`, `id="skills"`, etc.) and edit the
  text in place.
- Contact links (email, GitHub) are set to `soumyajit.das24@tnu.in` and
  `github.com/Zen-Zero10` — update both in the nav, hero, and contact section if
  they ever change.
- The "View on GitHub" button under the Flight Price Prediction project currently
  points to my GitHub profile. Once that project has its own repo, swap that link to
  the repo's actual URL.

## Contact

- Email: [soumyajit.das24@tnu.in](mailto:soumyajit.das24@tnu.in)
- GitHub: [github.com/Zen-Zero10](https://github.com/Zen-Zero10)
- Location: Diamond Harbour, West Bengal, India
