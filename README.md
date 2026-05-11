# Thriving While Detonating

Project website for the NSF DMREF project *"Thriving While Detonating — Materials for Extreme Dynamic Thermomechanical Performance"* (NSF Award [#2522673](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2522673)).

A multi-institutional collaboration between **Lehigh University**, **UC Irvine**, and **Carnegie Mellon University**, in partnership with the **Air Force Research Laboratory** and industry collaborators, working on materials for rotating detonation engines.

## Site structure

```
.
├── index.html              # Project front page
├── workshop_2026/          # Archived 2026 RDE Materials Workshop site
│   └── index.html
└── assets/
    ├── hero-bg.png
    ├── nsf_dmref_logo.png
    ├── uci_engineering_logo.png
    ├── AFRL_logo.png
    ├── boeing_logo.png
    ├── ati_logo.png
    ├── RDE_AFRL_overview.png
    ├── dmref_cycle_chart.png
    └── people/             # Team portraits (jpg, square crops)
```

The page is a single static HTML file with inline CSS — no build step. Edit `index.html` directly and push.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000/ in a browser
```

## Hosting

Served via GitHub Pages from the `main` branch root. To enable on a fresh repo:
**Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)`**.

## Acknowledgment

This material is based upon work supported by the National Science Foundation under Award No. 2522673. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the NSF.
