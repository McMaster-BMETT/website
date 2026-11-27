# McMaster BMETT

Production: https://mcmasterbmett.ca

A responsive static site with the official BMETT logo, original team cards and photographs, TrACL project details, current and past events, team filters, event dialogs, a downloadable calendar event, and FAQ.

## Preview locally

Run `python3 -m http.server 4173 --directory dist`, then open http://localhost:4173.

## Update

Edit `dist/index.html`, `dist/styles.css`, `dist/typography.css`, and `dist/app.js`. Readable text sizes and responsive adjustments are in `dist/typography.css`. Event records and leadership data are in `dist/app.js`. Source verification notes are in `RESEARCH.md`. Information was checked on November 4, 2026; recruitment and event availability should be refreshed as announcements change.

## Deploy

Push updates to `main` in [McMaster-BMETT/website](https://github.com/McMaster-BMETT/website). Production hosting is managed by BMETT's Vercel account for `mcmasterbmett.ca`. The included `vercel.json` serves `dist/` without a build or package installation.

The former `mcmaster-bmett` project in `aadithyataruns-projects` has been retired. Do not deploy to that account.

Local environment files, credentials, and hosting account settings are excluded from Git.
