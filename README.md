# Marketing Professional Portfolio

A premium, single-page portfolio website built for Kanishka Virmani, a Marketing Professional and MBA Candidate.

## Features
- **Single Page Architecture**: All content is contained within a single `index.html` file, including inline CSS and JavaScript.
- **Modern Aesthetic**: Features a dark, glassmorphic design language with vibrant gradient accents and ambient glowing backgrounds.
- **Fully Responsive**: Optimized for desktop, tablet, and mobile viewing.
- **Interactive Elements**: Smooth scrolling navigation, Intersection Observer-based reveal animations, and a sticky navigation bar with active state tracking.
- **Zero Dependencies**: Built with pure HTML/CSS/JS (Vanilla). The only external assets are Google Fonts (Inter and Outfit).

## Deployment

This repository is configured to automatically deploy to GitHub Pages whenever changes are pushed to the `main` branch, using GitHub Actions.

### Setup Instructions (For the Repository Owner)

1. Make sure this repository is public (or if private, ensure you have GitHub Pro/Team for private Pages).
2. Go to your repository settings on GitHub.
3. Navigate to **Pages** in the left sidebar.
4. Under **Build and deployment > Source**, ensure **GitHub Actions** is selected.
5. Push your code to the `main` branch:

```bash
git add .
git commit -m "Initial commit"
git push origin main
```

6. GitHub Actions will automatically trigger. You can check the progress in the **Actions** tab of your repository.
7. Once deployed, the site will be live at `https://[your-username].github.io/[your-repo-name]/`.

## Customization

To edit the portfolio contents, open `index.html` in your favorite code editor and modify the sections. The structure is separated into clear semantic blocks (`#home`, `#about`, `#experience`, `#contact`).

The CSS color variables at the top of the `<style>` block control the main theme:

```css
:root {
    --bg-dark: #0a0a0f;
    --text-main: #f3f4f6;
    --text-muted: #9ca3af;
    --accent-primary: #8b5cf6; /* Violet */
    --accent-secondary: #ec4899; /* Pink */
    /* ... */
}
```
