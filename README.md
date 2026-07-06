# Oddly's Blog — [oddly-augmented.github.io](https://oddly-augmented.github.io)

A personal blog covering recipes, art, 3D modeling, and whatever else is on my mind. Built with plain HTML/CSS and Jekyll for post management, hosted on GitHub Pages.

```
## Project Structure

```
oddly-augmented.github.io/
├── _config.yml          # Jekyll site settings
├── _layouts/
│   ├── default.html     # Shared header/nav shell
│   └── post.html        # Individual blog post wrapper
├── _posts/              # Blog posts as Markdown files
│   └── YYYY-MM-DD-slug.md
├── _images/
├── blog/
│   └── index.html       # Blog listing page
├── recipes/
│   └── index.html       # Recipes page
├── index.html           # Homepage
└── index.css            # Global styles

```

---

## Writing a New Post

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md`

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
### Post Format
| Value       | Effect                                 |
| ----------- | -------------------------------------- |
| (omitted)   | Auto-alternates left/right by position |
| image-left  | Always image on left                   |
| image-right | Always image on right                  |
| text-only   | No image shown                         |
| image-hero  | Full-width image above text            |

---

## Pages

| URL | Description |
|-----|-------------|
| `/` | Homepage with featured posts |
| `/blog/` | Full post listing |
| `/recipes/` | Recipes section (coming soon) |
| `/gallery/` | Gallery (coming soon) |
| `/subscribe/` | Subscribe (coming soon) |
