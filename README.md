# RAI — Revenue Analytics Intelligence

Single-file hackathon prototype. Everything (HTML, CSS, JavaScript) is inside `index.html`.

## Run
- **VS Code:** open the folder, right-click `index.html` → *Open with Live Server*.
- **Or just double-click** `index.html` (needs internet for Chart.js and Google Fonts).
- **GitHub Pages:** push `index.html` to a repo → Settings → Pages → deploy from `main` / root.

## Demo logins (fictional, local only)
| Company | Username | Password |
|---|---|---|
| RAI Growth Industries | growth_admin | RAI@Growth150 |
| RAI Challenge Enterprises | challenge_admin | RAI@Loss50 |
| RAI Balanced Ventures | balanced_admin | RAI@Balance110 |

The Demo Access buttons on the login screen fill these in.

## What is real vs planned
- **Built:** login/logout, 3 separate datasets, 8 working pages, calculations, straight-line forecast, rule-based findings engine, report print/download, themes, settings, calculation self-test (Settings → Run calculation tests).
- **Not built:** server-side authentication, database, real AI/LLM. The "AI" is a rule-based prototype. Passwords in this file are visible to anyone; use a backend (e.g. FastAPI) for real login.

## Edit the data
Open `index.html`, find `const D = {` — all figures are there (₹ crore). Set `end:90` for Balanced Ventures to show the ₹90 Cr scenario.
