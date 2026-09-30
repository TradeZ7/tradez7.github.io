# tradez7.com

The TradeZ website — plain HTML and CSS, served free by GitHub Pages.

| File | What it is |
| --- | --- |
| `index.html` | Home page |
| `download/index.html` | Download page (button points at the GitHub Release) |
| `update.json` | What installed copies of TradeZ read once a day to learn about new versions |
| `assets/` | Stylesheet, screenshots, icons |
| `CNAME` | Tells GitHub Pages the site lives at tradez7.com |

## New version checklist
1. Build the installer, then here on GitHub: Releases → Draft a new release → tag `vX.Y.Z` → attach `TradeZ-Setup-X.Y.Z.exe` → Publish.
2. In `download/index.html` and `index.html` change the version, date, size and the download link.
3. In `update.json` change `version`, `date` and `notes`.
4. Commit and push. The site updates in about a minute; every installed TradeZ sees the new version within a day.
