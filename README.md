# dm-dashboard-preview

A simple dashboard preview webpage published through GitHub Pages.

## GitHub Pages Setup

This repository is configured to automatically deploy to GitHub Pages using GitHub Actions.

### Enabling GitHub Pages

To enable GitHub Pages for this repository:

1. Go to the repository settings on GitHub
2. Navigate to **Settings** > **Pages**
3. Under **Source**, select **GitHub Actions**
4. The site will be automatically deployed when changes are pushed to the `main` branch or `copilot/publish-webpage-github-pages` branch

Once enabled, the site will be available at: `https://nerathul.github.io/dm-dashboard-preview/`

### Manual Deployment

You can also trigger a manual deployment:

1. Go to the **Actions** tab
2. Select the "Deploy to GitHub Pages" workflow
3. Click "Run workflow"