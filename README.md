# Oddly's Blog — [oddly-augmented.github.io](https://oddly-augmented.github.io)

A personal blog covering recipes, art, 3D modeling, and whatever else is on my mind. Built with plain HTML/CSS and Jekyll for post management, hosted on GitHub Pages.

---

## Stack

- **GitHub Pages** — free hosting, auto-deploys on push to `main`
- **Jekyll** — static site generator built into GitHub Pages; powers the blog
- **Liquid** — Jekyll's templating language used in layouts and the blog index
- **Fonts** — Montserrat (body) + Noto Serif (headings) via Google Fonts

---

## Project Structure

```
oddly-augmented.github.io/
├── _config.yml          # Jekyll site settings
├── _layouts/
│   ├── default.html     # Shared header/nav shell
│   └── post.html        # Individual blog post wrapper
├── _posts/              # Blog posts as Markdown files
│   └── YYYY-MM-DD-slug.md
├── blog/
│   └── index.html       # Blog listing page
├── index.html           # Homepage
└── index.css            # Global styles
```

---

## Writing a New Post

1. Create a file in `_posts/` named `YYYY-MM-DD-your-title.md`
2. Add front matter at the top:

```markdown
---
layout: post
title: "Your Post Title"
category: Recipes
date: 2026-06-29
image: /path-to-image.png
---

Your post content in Markdown...
```

3. Commit and push to `main` — GitHub Pages rebuilds automatically (~60 seconds)

---

## Pages

| URL | Description |
|-----|-------------|
| `/` | Homepage with featured posts |
| `/blog/` | Full post listing |
| `/recipes/` | Recipes section (coming soon) |
| `/gallery/` | Gallery (coming soon) |
| `/subscribe/` | Subscribe (coming soon) |
