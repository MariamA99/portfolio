# Research Portfolio — GitHub Pages starter

A complete, free, static research portfolio website with a homepage and four dedicated project pages. **No source-code publication is required for the projects described.** This repository itself contains only the portfolio website's HTML/CSS and illustrative SVG assets.

## Make it your own

1. Edit `index.html`: change **Your Name**, introductory text, contact email `you@example.com`, and LinkedIn URL.
2. Edit each file in `projects/`: replace the draft descriptions, result placeholders and publication details with your verified content.
3. Replace the SVG illustrations in `assets/` with your actual plots, diagrams or experimental figures when ready. You can use PNG, JPG, WebP or SVG; update image filenames in the respective HTML pages (and on `index.html` for cards). Only share images you have permission to publish.
4. Optional: update colours and fonts in `style.css`.

## Preview locally

Double-click `index.html`. The other pages use relative links, so they work locally too. A web server, Node.js, Python, Git, and any build tools are **not** required.

## Publish for free on GitHub Pages

1. Create a **public** GitHub repository named exactly `YOURUSERNAME.github.io`, where `YOURUSERNAME` is your GitHub account name.
2. Upload the **contents** of this folder directly to the repository root: `index.html`, `style.css`, `.nojekyll`, `assets/`, `projects/`, and optionally `README.md`. **Do not** upload the outer enclosing folder as an extra directory.
3. Commit the upload to the `main` branch.
4. In the repository, select **Settings → Pages → Build and deployment**.
5. Set **Source** to **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
6. Visit `https://YOURUSERNAME.github.io` once GitHub reports the deployment is complete (publication can take a few minutes).

## Site structure

```text
index.html                   Homepage + project cards
style.css                    All styling and responsive layout
.nojekyll                    Publish the static HTML directly
projects/
  modulation-recognition.html
  nonlinearity-compensation.html
  frequency-estimation.html
  direction-of-arrival.html
assets/
  amr.svg
  nonlinear.svg
  frequency.svg
  doa.svg
README.md                    These instructions
```

## Add another project

Copy one of the HTML files in `projects/`, rename it, edit its content, add its illustration to `assets/`, and duplicate one project-card link in the `index.html` projects grid. Links are ordinary relative HTML links.

## Important

All included visualisations are **illustrative placeholders**, not experimental results. Several paragraphs are example wording and should be checked against your actual work and any confidentiality/publication restrictions before sharing publicly. Github Pages exposes the website publicly, and the source files of a public repository are visible to others — this website does not contain the code for your research projects.
