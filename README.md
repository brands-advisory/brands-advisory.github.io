# brands-advisory.github.io

Website for brands-advisory.com

## Structure

This repository contains the website for Brands Advisory, which is deployed via GitHub Pages.

- `site/` - Contains the website files that will be published
- `.github/workflows/pages.yml` - GitHub Actions workflow for automated deployment

## Deployment

The website is automatically deployed to GitHub Pages when changes are pushed to the `main` branch. The workflow deploys the contents of the `site/` directory.

## Local Development

To view the website locally, simply open `site/index.html` in a web browser.

## GitHub Pages Configuration

After merging to main, ensure that GitHub Pages is configured in the repository settings:
- Go to Settings > Pages
- Source should be set to "GitHub Actions"
