# amogh

Private family planning dashboard for Amogh's Fall 2027 university applications.

**This is not a public document.** It is hosted on GitHub Pages because that is
convenient, not because it is meant to be read by anyone outside the family.
`robots.txt` and page-level meta tags ask search engines and AI crawlers not to
index or train on it. Those directives are voluntary. Treat the URL as the only
access control there is, and do not post it anywhere.

Live site: https://mailtovmat.github.io/amogh/

## Pages

| Page | File |
|---|---|
| Dashboard | `index.html` |
| Applications | `applications.html` |
| Progress | `progress.html` |
| Calendar | `calendar.html` |
| People | `people.html` |
| Docs | `docs.html` |
| Financial Aid | `financial.html` |

Design follows the College Tracker redesign (Plus Jakarta Sans, pill nav,
KPI cards, plan gantt). Data is the real vault — not the sample
Stanford / Purdue / accepted-offer numbers from the mock.

## Editing

Source of truth is the markdown vault at `C:\Amogh-Saanvi-College\Amogh`
plus `DETAILED APPLICATION PLAN.xlsx` and `Amogh-Saanvi-University-List.xlsx`.

Change what the site shows by editing `js/data.js`. `PUBLIC = true` in that
file hides the SAT score and the Financial Aid page content.

Every date marked `TBD-VERIFY` is unconfirmed. Do not invent a deadline
to fill a blank.
