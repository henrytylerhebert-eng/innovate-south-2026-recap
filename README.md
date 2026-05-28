# Innovate South 2026 Event Recap

Premium static editorial recap for Innovate South 2026 in Lafayette, Louisiana.

The site is intentionally simple: one static `index.html` file, local image assets, and no build step. It is designed to publish cleanly through GitHub Pages and to remain easy to archive, review, and update.

## Live Site

After GitHub Pages finishes deploying, the public URL should be:

<https://henrytylerhebert-eng.github.io/innovate-south-2026-recap/>

## Project Structure

- `index.html` - complete single-page recap with scoped CSS and vanilla JavaScript.
- `images/` - event photos and logo assets referenced by the page.
- `docs/` - operating notes for deployment, source handling, and content governance.
- `.github/workflows/pages.yml` - GitHub Pages deployment workflow.

## Local Preview

Open `index.html` directly in a browser, or run:

```bash
npm run serve
```

Then visit <http://localhost:8000>.

## Editing Rules

- Keep this as a vanilla HTML/CSS/JS static site.
- Do not introduce React, Tailwind, or a build pipeline without a deliberate repo decision.
- Keep photos in `images/` and reference them with relative paths.
- Preserve transcript/source boundaries for speaker claims, names, and session framing.

## Rights And Usage

This repository contains event copy, photography, and brand assets for Innovate South-related recap use. Do not treat the contents as open-source licensed material unless a license is added later by the project owner.
