# Electrum Wallet Guide — GitHub + Render

Independent educational SEO site about the Electrum Bitcoin wallet.

## GitHub repository name
`electrum-wallet-guide`

## Deploy on Render without terminal

### Static Site
1. Upload all project files to the ROOT of the GitHub repository.
2. Render > New > Static Site.
3. Connect the GitHub repository.
4. Branch: `main`
5. Build Command: `echo "Static site ready"`
6. Publish Directory: `.`
7. Create Static Site.

The repository also includes `render.yaml` for Render Blueprint deployment.

## Canonical domain
Preconfigured as:
`https://electrum-wallet-guide.onrender.com`

If Render assigns a different URL, replace the domain in every canonical/og:url plus:
- robots.txt
- sitemap.xml
- sitemap.txt

## Search Console
See `SEARCH-CONSOLE.txt`.

## Identity and safety
This is an independent guide. It does not host wallet installers, ask for seed phrases/private keys, process transactions, or represent itself as the official Electrum project.
