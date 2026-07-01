# yigitalijonolimjonov-de.github.io

Personal portfolio of **Yigitalijon Olimjonov** — Data Analyst, BI Developer, and aspiring Data Engineer.

🔗 **Live site:** https://yigitalijonolimjonov-de.github.io

---

## What's here

| Section | Content |
|---|---|
| About | Bio, skills, and contact links |
| Dashboards | Power BI and Metabase project showcase |
| Learning path | BI → Analytics Engineering → Data engineering skill tracker |

## Stack

- Plain HTML + CSS (no framework, no build step)
- Hosted free on GitHub Pages
- Fonts: Inter + JetBrains Mono via Google Fonts

## How to run locally

```bash
# Just open the file in a browser — no server needed
open index.html
```

Or use any static file server:

```bash
npx serve .
```

## Adding a new dashboard

1. Take a screenshot of your Power BI report → save to `assets/images/dashboards/`
2. Copy one of the `.dash-card` blocks in `index.html`
3. Update the name, description, tags, and `href` (Power BI publish-to-web URL)
4. Push to `main` — GitHub Pages deploys automatically

## Updating the learning path

Edit the `width` percentage on each `.node-bar-fill` in the learning path section.  
Change the dot class (`done` / `doing` / `next`) and status badge text to match.

---

Built and maintained by [Yigitalijon Olimjonov](https://github.com/yigitalijonolimjonov-de)
