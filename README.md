# DMA Cert - Jekyll Site

A Jekyll static site deployed to GitHub Pages using GitHub Actions.

## Setup

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Build the site locally:**
   ```bash
   bundle exec jekyll build
   ```

3. **Serve the site locally:**
   ```bash
   bundle exec jekyll serve
   ```
   Then visit `http://localhost:4000` in your browser.

## Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions whenever you push changes to the `main` branch.

The workflow:
1. Builds the Jekyll site
2. Uploads the built site as an artifact
3. Deploys to GitHub Pages

## Configuration

- `_config.yml` - Jekyll configuration
- `.github/workflows/jekyll.yml` - GitHub Actions workflow

## Learn More

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)

