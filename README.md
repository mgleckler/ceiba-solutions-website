# Ceiba Solutions Website

Static HTML site designed for Cloudflare Pages.

## Deploy
- Put `index.html` in a GitHub repository.
- Cloudflare Pages: Workers & Pages → Create application → Pages → Import Git repository.
- Production branch: `main`
- Build command: `exit 0`
- Build output directory: `/` (or the repository root, depending on the current Cloudflare UI).

Then add `ceiba-solutions.com` under Custom domains.

## Before launch
Replace the placeholder LinkedIn URL and confirm the desired public email address.
