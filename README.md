# Random Marcus Aurelius Quotes

A minimalist webpage displaying random quotes from Marcus Aurelius' *Meditations*.

## Features

- 79 authentic quotes from Marcus Aurelius' *Meditations* (George Long translation)
- Minimalist modern Greek design with white background and black text
- Circular refresh button with smooth animations
- Fully responsive for mobile and desktop
- No dependencies - pure HTML, CSS, and JavaScript

## GitHub Pages Setup

This repository is configured with automated GitHub Pages deployment using GitHub Actions.

### Automated Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` or `master` branch. The GitHub Actions workflow (`.github/workflows/deploy.yml`) handles the build and deployment process.

**Site URL:** `https://thvanderwal.github.io/randommarcus/`

### Manual Setup (One-time)

If this is the first deployment, ensure GitHub Pages is enabled in your repository:

1. Go to your repository settings on GitHub
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "GitHub Actions"
4. The site will automatically deploy on the next push to main/master

### Manual Deployment

You can also trigger a manual deployment:
1. Go to the "Actions" tab in your repository
2. Select "Deploy to GitHub Pages" workflow
3. Click "Run workflow"

## Local Development

To run locally, simply open `index.html` in your browser or use a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/index.html`

## Quote Authenticity

All quotes are verified authentic quotes from Marcus Aurelius' *Meditations*, sourced from the respected George Long translation. Each quote includes a reference to its book in the Meditations.