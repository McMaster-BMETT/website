# McMaster BMETT

Production: https://mcmaster-bmett.vercel.app

A responsive static site with the official BMETT logo, original team cards and photographs, TrACL project details, current and past events, team filters, event dialogs, a downloadable calendar event, and FAQ.

## Preview locally

Run `python3 -m http.server 4173 --directory dist`, then open http://localhost:4173.

## Update

Edit `dist/index.html`, `dist/styles.css`, and `dist/app.js`. Event records and leadership data are in `dist/app.js`. Source verification notes are in `RESEARCH.md`. Information was checked on November 4, 2026; recruitment and event availability should be refreshed as announcements change.

## Deploy

Deploy this folder to the existing Vercel project `mcmaster-bmett` in `aadithyataruns-projects`. The included `vercel.json` serves `dist/` without a build or package installation.

Local environment files, credentials, and hosting account settings are excluded from Git.
