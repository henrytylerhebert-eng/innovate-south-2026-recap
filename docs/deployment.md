# Deployment

This site deploys through GitHub Pages using the workflow at `.github/workflows/pages.yml`.

## Publish Flow

1. Edit `index.html` and/or files under `images/`.
2. Preview locally:

   ```bash
   npm run serve
   ```

3. Commit changes to `main`.
4. Push to GitHub.
5. GitHub Actions deploys the static site to GitHub Pages.

## Expected Public URL

<https://henrytylerhebert-eng.github.io/innovate-south-2026-recap/>

## Custom Domain Option

For a more polished public URL, connect a subdomain such as:

- `recap.innovatesouth.org`
- `2026.innovatesouth.org`

When the final domain is chosen, add a `CNAME` file at the repository root containing only the custom domain.

## Wix Integration

The recommended Wix integration is to link to the GitHub Pages URL from a Wix menu/button, or point a Wix-managed subdomain to the published recap. Embedding the recap inside a Wix iframe is possible, but should be treated as a fallback because height and mobile behavior may need extra tuning.
