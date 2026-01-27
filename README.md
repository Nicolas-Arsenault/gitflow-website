# GitFlow Website

Landing page and documentation for GitFlow - A free, professional-grade Git GUI for macOS.

## Pages

- `index.html` - Landing page with features overview
- `docs.html` - Full documentation

## Deployment

This site uses GitHub Actions for automatic deployment to GitHub Pages.

### Setup

1. Push this repository to GitHub
2. Go to repository **Settings** → **Pages**
3. Under "Build and deployment", select **GitHub Actions** as the source
4. The site will deploy automatically on every push to `main`

### Manual Trigger

You can also manually trigger a deployment from the **Actions** tab → **Deploy to GitHub Pages** → **Run workflow**.

## Development

Open `index.html` in a browser to preview locally. No build step required.

## Structure

```
gitflow-website/
├── index.html              # Landing page
├── docs.html               # Documentation
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml      # GitHub Actions deployment
```

## License

MIT
