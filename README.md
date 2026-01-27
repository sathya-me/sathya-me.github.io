# sathya.me

Personal website for Sathya Narayanan.

## Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions. The workflow is triggered on every push to the `main` branch.

### GitHub Pages Setup

To enable GitHub Pages deployment:

1. Go to your repository Settings
2. Navigate to Pages (under "Code and automation")
3. Under "Build and deployment":
   - Source: Select "GitHub Actions"
4. The workflow will automatically deploy on the next push to `main`

### Workflow

The deployment workflow (`.github/workflows/deploy-pages.yml`) automatically:
- Checks out the repository
- Configures GitHub Pages
- Uploads the static site as an artifact
- Deploys to GitHub Pages

### Manual Deployment

You can also trigger a deployment manually:
1. Go to the Actions tab
2. Select "Deploy to GitHub Pages" workflow
3. Click "Run workflow"

## Local Development

This is a static HTML site. Simply open `index.html` in a browser to view locally.

## License

© 2021 Sathya Narayanan
