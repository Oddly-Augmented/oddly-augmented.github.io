---
# ============================================================
# REQUIRED — fill these out for every post
# ============================================================
layout: post
title: "Your Post Title Here"
date: 2026-07-27          # YYYY-MM-DD — controls sort order and URL slug date

# ============================================================
# SEO FIELDS — added in Module 5, fill out for every post
# ============================================================
description: "One or two sentences describing this post. This shows up as the Google search snippet, so make it specific and useful. ~150 characters ideal."
image_alt: "Describe the image clearly — e.g. 'A golden sourdough loaf on a wooden cutting board, freshly scored'"

# ============================================================
# DISPLAY / CARD OPTIONS
# ============================================================
category: Recipes         # Options: Recipes | Art | Blog (controls the tag pill color)
image: /images/your-image-filename.jpg   # Path to your post image in /images/
card_style: auto          # Options: auto | image-right | text-only | image-hero
excerpt: "A short teaser shown on the homepage card. Keep it to one sentence."

# ============================================================
# OPTIONAL — remove if unused
# ============================================================
# tags: [sourdough, baking, bread]
# ============================================================
---

<!-- Hero image — update src and alt to match your front matter above -->
<figure class="post-image">
  <img src="{{ page.image }}" alt="{{ page.image_alt }}">
  <figcaption>Optional caption text — or delete this line</figcaption>
</figure>

## Introduction

Write a short intro paragraph here. What is this post about? Why did you make/do this? Keep it conversational — this is your voice.

---

## Section Heading

Add your main content here. Use `##` for major sections and `###` for subsections, matching the existing posts.

You can use **bold** for emphasis and *italics* sparingly.

### Subsection

- Bullet point one
- Bullet point two
- Bullet point three

---

## Another Section

Continue writing here. Add as many `##` sections as your content needs.

If it's a recipe, consider sections like:
- Ingredients
- Instructions
- Tips & Variations

If it's an art or blog post, just use sections that match the flow of your writing.
