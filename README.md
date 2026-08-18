# amogh

Private family planning dashboard for Amogh's Fall 2027 university applications.

**This is not a public document.** It is hosted on GitHub Pages because that is
convenient, not because it is meant to be read by anyone outside the family.
`robots.txt` and page-level meta tags ask search engines and AI crawlers not to
index or train on it. Those directives are voluntary. Treat the URL as the only
access control there is, and do not post it anywhere.

Live site: https://mailtovmat.github.io/amogh/

Tabs: Dashboard · Progress · Calendar · Docs-status · G-Drive · Universities · Financial Aid · People.

Every page load, browser refresh, and the blue **Refresh** button reloads **Tasks** and **Documents Needed** from Amogh's application-plan spreadsheet, and rebuilds the G-Drive file tree from the live vault (markdown notes stay hidden). Universities, aid, people, and the gantt still come from the committed JS files.

Sources: `C:\Amogh-Saanvi-College\AMOGH-DASHBOARD-SOURCES.md`  
Setup (what you still have to click): `C:\Amogh-Saanvi-College\AMOGH-SETUP.md`

## Editing

The live due-by lists come from [application-plan](https://docs.google.com/spreadsheets/d/1wBEKPcSzR4uXTwoTKSH_U2THZFg8M-oy/edit). Edit Tasks / Documents Needed there, then Refresh.

`PUBLIC = true` in `js/data.js` hides the SAT score and the Financial Aid page content.

Every date marked `TBD-VERIFY` is unconfirmed. Do not invent a deadline
to fill a blank.
