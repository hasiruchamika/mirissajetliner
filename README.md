# Mirissa Jetliner

Short demo/static frontend for Mirissa Jetliner.

## What this repo contains
- Minimal static frontend scaffolding (index.html stub)
- A sample bookings text file in the repo root (review and remove if it contains PII)
- A Maven pom.xml (if backend/build is present)

## Local development
This repo currently contains static HTML. To serve locally:
- Use a static server (e.g., `npx http-server .` or open index.html in your browser).

## Suggested next steps
1. Remove or sanitize `Using a text file (e.g., bookings.t.txt)` if it contains any real user data. Replace with `bookings.sample.txt` for demo data.
2. Add a proper `public/` structure: `/index.html`, `/css/`, `/js/`, `/assets/`.
3. Add CI checks: htmlhint, stylelint, axe accessibility checks, and Lighthouse (lhci).
4. Rename `versel.json` → `vercel.json` if deploying to Vercel.
5. Remove `.idea/` from the repository and add to `.gitignore`.

## License
Add an appropriate LICENSE file.