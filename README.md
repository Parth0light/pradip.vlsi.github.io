# VLSI Hub — GitHub Pages Site

## Quick Start
1. Create a new GitHub repo named `<your-username>.github.io`.
2. Download this zip and upload all files to the repo root.
3. Commit and push. GitHub Pages will publish automatically (Settings → Pages → Source: Deploy from a branch, branch: `main`).
4. Edit `_config.yml` to set your `url`, social links, and AdSense client ID.
5. Replace affiliate links in `_includes/affiliate/links.html`.
6. Add posts in `_posts/` and tutorials in `_tutorials/`.

## Writing a blog post
Create a file like `_posts/2025-09-02-my-post.md`:

```yaml
---
title: My Post
tags: [verilog, tips]
---
Write your content here.
```

## Writing a tutorial
Create a file in `_tutorials/my-tutorial.md`:

```yaml
---
title: My Tutorial
summary: What this teaches.
---
Content...
```

## Q&A
For now, enable **GitHub Discussions** in your repo and link it from `/qa/`.
