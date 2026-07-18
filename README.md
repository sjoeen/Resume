# CV Landing Page

A simple landing page linked from the QR code on my business card. Lets people view my CV (Norwegian or English) and recommendation letter directly in the browser, without downloading anything first.

**Live site:** https://sjoeen.github.io/Resume/

## How it works

- `index.html` — the page itself (design, tabs, PDF viewer)
- `cv-no.pdf` — CV in Norwegian
- `cv-en.pdf` — CV in English
- `anbefaling.pdf` — recommendation letter
- `logo.png` — university logo shown in the header

PDFs are rendered inline via Google Docs Viewer so they display correctly across regular browsers and in-app browsers (e.g. Instagram, LinkedIn), which often can't render PDFs in a plain iframe.

## Updating

To update any document, just replace the file in this repo with a new one **using the exact same filename**. The site and the QR code on the printed card never need to change.

Changes go live automatically within a minute or two via GitHub Pages.
