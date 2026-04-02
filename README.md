# Radu Paun — Author Website

Personal author website for Radu Paun, built as static HTML/CSS for hosting on GitHub Pages.

## Files

```
/
├── index.html          # Homepage
├── for-agents.html     # For literary agents
├── projects.html       # Projects & progress tracker
├── about.html          # Bio & reading influences
└── css/
    └── style.css       # Shared styles
```

## Hosting on GitHub Pages

### First time setup

1. Create a new repository on GitHub — name it exactly `yourusername.github.io`
   (e.g. `radupaun.github.io`) for a root site, or any name for a project site.

2. Upload all files, keeping the folder structure intact.

3. Go to **Settings → Pages** in your repository.

4. Under **Source**, select `Deploy from a branch` and choose `main` (or `master`).

5. Save. Your site will be live at `https://yourusername.github.io` within a minute or two.

### Custom domain (recommended)

If you have a domain like `radupaun.com`:

1. In your DNS provider, create a `CNAME` record pointing to `yourusername.github.io`.
2. In **Settings → Pages → Custom domain**, enter your domain.
3. Check "Enforce HTTPS" once it propagates (can take a few hours).

### Updating the site

Edit any `.html` file and push to the `main` branch — GitHub Pages deploys automatically.

## Customising content

All placeholder text is marked with `[square brackets]`. Things to fill in:

- **index.html** — tagline in the hero section, intro paragraphs
- **for-agents.html** — bio paragraphs, comp titles in the sidebar
- **projects.html** — replace the three example rows with your real projects
- **about.html** — full bio, short bio, reading interests tags, influences grid
- **All pages** — replace `https://instagram.com/` with your actual Instagram URL

## Social links

Currently configured:
- Instagram — update the `href` in all four pages
- Bluesky — marked as "coming soon"; replace `href="#"` with your URL when ready

To add more platforms, copy the pattern in the `.footer-social` and `.social-list` sections.
