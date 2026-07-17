Ngoc-Au Doan — Personal site

This repository contains a simple GitHub Pages site for the CV and blog of Ngoc-Au Doan.

License: MIT — see [LICENSE](LICENSE)

Structure overview
- `index.html` — main CV (static HTML)
- `blog/` — blog index and posts (HTML placeholders)
- `blog/_posts/` — recommended location for Markdown posts (Jekyll-style)
- `blog/posts/` — HTML versions of posts (category folders)
- `assets/images/` — global images (avatar, logos)
- `assets/posts/` — per-post image folders (e.g. `assets/posts/2026-07-17-welcome-to-blog/`)
- `assets/archive/` — archived images moved during cleanup
- `resume/` — resume PDF(s)
- `_config.yml` — minimal Jekyll metadata (optional; keep if you use GitHub Pages with Jekyll)

What I changed
- Moved global images into `assets/images/` and created `assets/posts/` for post images.
- Moved resume PDF into `resume/`.
- Added a sample Markdown post at `blog/_posts/2026-07-17-welcome-to-blog.md` and an HTML view at `blog/posts/image-processing/welcome-to-blog.html`.

How to add a new post (recommended)
1. Create a Markdown file in `blog/_posts/` with Jekyll front matter (see sample file). Filename format: `YYYY-MM-DD-your-slug.md`.
2. Place images used by the post in `assets/posts/<your-slug>/` and reference them by absolute path (e.g. `/assets/posts/your-slug/figure1.png`).
3. Push to GitHub. If you use Jekyll on GitHub Pages the `_posts` files will be rendered automatically. If you prefer static HTML, create an HTML file under `blog/posts/<category>/`.

Quick commands (PowerShell) to remove archive if desired:

```powershell
Remove-Item -Path .\assets\archive\* -Force
```

If you want me to also add a GitHub Actions workflow to build/preview the site or convert Markdown posts into HTML automatically, tell me and I'll scaffold it.
