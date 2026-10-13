# Anuja Tripathi, PhD

Personal academic website. Static HTML, no build step.

- `index.html` is the live site (currently the Editorial layout).
- `preview/` holds the five layout options, each with a text colour picker. Vercel serves them at `/preview/<name>` and marks them `noindex`.

## Deploy on Vercel

1. Import this repository in Vercel (Add New, Project, Import Git Repository).
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Deploy. Every push to `main` redeploys automatically.

To switch the live layout, copy the chosen file from `preview/` to `index.html` and remove the colour picker script, or ask Claude to rebuild it.
