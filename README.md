# EE5531 Introduction to Robotics: Course Website & Flyer

Recruiting site for EE5531, served by GitHub Pages at
**https://robust-autonomous-systems-laboratory.github.io/ee5531/**

| Path | What it is |
|------|------------|
| `index.html`, `style.css` | The course website (static, no build step) |
| `assets/` | Jackal photo and Husky Plaza point-cloud renders |
| `flyer/flyer.html` | Flyer source (8.5×11, print CSS) |
| `flyer/flyer.pdf` | Print-ready flyer, linked from the website |
| `flyer/flyer_preview.png` | PNG preview of the flyer |
| `flyer/qr_ee5531.svg` | QR code → the site URL above |
| `flyer/logos/` | Employer logos used on the flyer only (see `SOURCES.md`) |

## Filling in the placeholders

Search for `[TBD` in `index.html` and `flyer/flyer.html`. Placeholders cover the term,
meeting days and time, room, credits, CRN, prerequisites, eligibility, and instructor contact.

## Regenerating the flyer PDF

The PDF is rendered from `flyer/flyer.html` with headless Chromium. Any Chromium-based
browser works: open `flyer/flyer.html`, print, choose **Letter**, set margins to **None**,
enable **Background graphics**, and save as PDF. From the command line:

```bash
chromium --headless --no-pdf-header-footer --print-to-pdf=flyer/flyer.pdf flyer/flyer.html
```

If the site URL ever changes, regenerate the QR code (for example
`python3 -m segno "<url>" --error m --scale 10 --border 2 --dark "#111214" -o flyer/qr_ee5531.svg`)
and update the URL text in `flyer/flyer.html` and the Open Graph tags in `index.html`.

## Point-cloud images

`assets/husky_plaza_*.jpg` are renders of the student-built map in
[RASL-MOLA-Husky-Plaza](https://github.com/Robust-Autonomous-Systems-Laboratory/RASL-MOLA-Husky-Plaza),
which the website embeds as a live 3D viewer.
