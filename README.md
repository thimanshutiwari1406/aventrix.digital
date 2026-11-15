# aventrix.digital — Next-Gen Digital Agency

A responsive static landing page based on the supplied Stitch HTML and DESIGN.md.

## Run locally

No build step is required. Open `index.html` in a browser, or run a local static server:

```bash
python -m http.server 4173
```

Then visit http://localhost:4173.

## Deploy to Vercel

Import this repository in Vercel. Framework preset: **Other**; Build Command: leave empty; Output Directory: `.`. The included `vercel.json` supplies clean URLs and basic security headers.

## GitHub

Create an empty GitHub repository, then run:

```bash
git init
git add .
git commit -m "Build Aventrix digital agency landing page"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

The contact actions use `mailto:hello@aventrix.digital`; replace the sample agency contact details, testimonials, metrics, and project imagery with verified business information before publishing.
