# Stany Arthur Gagnaux — Portfolio site

Personal portfolio. Plain HTML/CSS, no build step. Hosts on GitHub Pages.

## Files

```
index.html              Main page
thesis.html             Master's thesis (WIP)
cerm.html               Sustainable lending research (WIP)
aura.html               Project AURA — ZHAW Innovation Weekend
cfa.html                CFA Research Challenge writeup
portfolio.html          Personal investment portfolio
assets/
  headshot.jpg          Profile photo
  cfa-cover.png         CFA report cover thumbnail
  cfa-sika-report.pdf   Full CFA Research Challenge paper
  aura-team.jpg         AURA team photo at ZHAW Innovation Weekend
  aura-pitch.mp4        AURA pitch video (compressed to 8.7MB)
  aura-poster.jpg       Video poster frame
  portfolio-overview.png   (legacy — not currently shown on portfolio page)
  portfolio-holdings-1.png (legacy — not currently shown on portfolio page)
  portfolio-holdings-2.png (legacy — not currently shown on portfolio page)
  cv.pdf                ← still need to add this
```

## Setup

1. Create a repo named `stanygagnaux.github.io` (or whatever you prefer)
2. Drop all files in the root, keeping the `assets/` structure
3. Add `assets/cv.pdf` so the Download CV button works
4. Settings → Pages → deploy from `main` branch root

## Behaviour summary

- Click **CFA Research Challenge** → opens the Sika PDF in a new tab
- Click **Master's Thesis** or **Sustainable Lending** → "Coming soon" toast appears (WIP)
- Click **Project AURA** → video modal opens, ESC closes, also has a link to the dedicated AURA page

## Stack

Inter from Google Fonts. No frameworks, no build tools, no JS dependencies beyond the small inline script for the modal.
