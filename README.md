# Hussein El-Taibee Seleem · Faculty Portfolio

Personal academic portfolio of **Dr. Hussein El-Taibee A. Seleem**, Associate Professor of Electronics and Electrical Communications (Tanta University) and Communication and Computers Engineering (CCE) Program Coordinator at Mansoura National University (MNU).

**Live site:** https://husseineltaibee.github.io/eltaibee/

## About

The site presents research in photonics and wireless communications: optical fibre design, optical CDMA, photonic-microwave integration, Li-Fi, 5G/mmWave, massive MIMO, and AI/ML for communications.

The home page has an interactive spectrum explorer. Drag the slider from optical fibre (about 193 THz) to 60 GHz millimetre-wave radio, and the animated wave and the page colour follow. Topics on the Research tab move the slider to where they sit on the spectrum.

## Tabs

| Tab | Contents |
|---|---|
| About | Summary, key numbers, roles, career path |
| Teaching | Courses by academic year and semester with code, level and credit hours; other courses taught; student supervision |
| Research | Research interests, laboratory experience, doctoral work, service |
| Projects | Nine funded research projects (KACST, NPST, MAARIFAH, Lockheed Martin, KSU) |
| Publications | Searchable list with Journal and Conference filters |
| Personal | Background, education, certifications, social links, contact |

## Tech

A single static file, `index.html`, with no build step and no dependencies other than Google Fonts. It supports light and dark mode, works on phones, respects reduced-motion settings, and each tab can be linked directly (for example `/#publications`).

## Run locally

Open `index.html` in any browser. No server is needed.

## Deploy on GitHub Pages

1. Name the repository `Husseineltaibee.github.io` and keep it public.
2. Put `index.html` and this `README.md` in the repository root.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, then **main** and **/ (root)**.
4. The site appears at `https://husseineltaibee.github.io` within a few minutes.

## Updating content

All content lives in `index.html`. The About, Research and Personal tabs are plain HTML. The other tabs are generated from text lists in the script at the bottom of the file:

- `C`: courses, one per line as `year|semester|code|name`
- `S`: supervised students, one per line as `student|thesis|degree · year`
- `P`: funded projects, one per line as `years|title|sponsor`
- `U`: publications, one per line as `year|J or C|venue|title`

Add or edit a line, commit, and the site updates within a minute or two.

## Connect

[LinkedIn](https://www.linkedin.com/in/hussein-seleem-bb2a418/) · [GitHub](https://github.com/Husseineltaibee) · [Tanta University page](https://tdb2.tanta.edu.eg/staff/eltaibee) · [X](https://x.com/eltaibee) · [Facebook](https://www.facebook.com/eltaibee) · [Instagram](https://www.instagram.com/eltaibee/)

ORCID: 0000-0002-2936-5447

## License

© Hussein El-Taibee Seleem. All rights reserved. Please do not reuse the text or publication list without permission.
