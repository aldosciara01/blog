# Cook Political Inspired Blog

This is a Jekyll-powered blog inspired by [Cook Political Report](https://www.cookpolitical.com), designed for easy publishing of news, reports, and analysis on political topics.

## Features

- **Home page** with recent and featured posts
- **Category/tag structure** for organizing content
- **Post previews** with publish date and excerpt
- **Responsive design** for desktop and mobile
- **About page** for information about the site or author
- **Easy editing:** posts and pages are Markdown files

## Getting Started

1. **Clone or fork this repository**
2. **Add your own posts:**
   - New articles go in the `_posts/` folder.
   - File format: `YYYY-MM-DD-title.md`
   - Use [Markdown](https://www.markdownguide.org/) and add frontmatter (see example below).

3. **Customize site configuration** in `_config.yml`
   - Change title, description, author info, base URL, and other settings.

4. **Deploy with GitHub Pages**
   - Go to repo settings → Pages → choose the branch (`main` or `master`) and root (`/`), then save.
   - Your site is live at `https://your-github-username.github.io/reponame`

## Example Post

```
---
title: "Election 2025 Preview"
date: 2025-11-10
categories: elections
excerpt: "A quick analysis of the upcoming 2025 elections."
---
The 2025 elections are coming soon...
```

## Customization

- **Styling:** Edit `assets/css/main.css` to change colors, fonts, layout.
- **Category navigation:** Add or edit categories in post frontmatter and sidebar in `index.html`.
- **Add pages:** Create new Markdown files (e.g., `about.md`) with a layout in the header.

## Useful Links

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Quickstart](https://docs.github.com/en/pages/getting-started-with-github-pages)
- [Markdown Guide](https://www.markdownguide.org/)
