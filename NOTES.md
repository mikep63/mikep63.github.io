# mikep63.github.io — Setup Notes

## Live Site
https://mikep63.github.io

## Repo
https://github.com/mikep63/mikep63.github.io
Branch: `main` — pushes auto-deploy via GitHub Pages

## How it was built
- Single `index.html` using [Pico CSS](https://picocss.com) via CDN
- No build tools, no dependencies — just edit and push
- Pico CSS CDN link: `https://cdn.jsdelivr.net/npm/@picocss/pico@2/css/pico.min.css`

## Key settings that were required
- Repo must be **Public** (GitHub Pages is free for public repos only)
- **Settings → Pages → Source** must be set to `main` branch
- First deploy can take 5–10 minutes

## Content links in the page
- LinkedIn: https://www.linkedin.com/in/mike-parker-73244023/
- HAM Radio (Extra class, KB4S): https://www.qrz.com/db/KB4S
- Amateur Astronomy: https://app.astrobin.com/u/mikeparker
- GitHub: https://github.com/mikep63

## To make changes
1. Edit `index.html` in VS Code
2. Commit and push via GitHub Desktop (or VS Code source control)
3. Site updates automatically within ~1 minute

## Structure of index.html
- Header: name, title, nav links
- About: short bio blurb
- Interests: cards linking to QRZ and AstroBin
- Career: full timeline from 1986 to present (Atos, Xerox, ACS, Anthem, Trigon, BCBS Virginia)
- Footer: name and location
