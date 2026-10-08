# Tithe Logistics — public site

Static GitHub Pages site (Jekyll, no theme, no plugins) for the Tithe Logistics Shopify app: landing page with demo video, Support, Privacy Policy, Terms of Service.

## Setup

1. Edit `_config.yml` — fill in every `[PLACEHOLDER]` once; all pages pull from it.
   - `youtube_id`: just the ID (e.g. `dQw4w9WgXcQ`), not the full URL.
   - `baseurl`: `/<repo-name>` for a project repo; `""` for a custom domain.
2. Search the pages for any remaining `[` brackets (carrier list in `support.md`, log retention in `privacy.md`).
3. Create a **public** repo (e.g. `tithelogistics-site`) on your account and push:
   ```sh
   git init -b main && git add . && git commit -m "Initial site"
   git remote add origin git@github.com:<username>/tithelogistics-site.git
   git push -u origin main
   ```
4. Repo → Settings → Pages → Source: **Deploy from a branch**, Branch: `main` / `(root)`.
5. Site goes live at `https://<username>.github.io/tithelogistics-site/` in a minute or two.

URLs for the Shopify Partner app listing:
- Privacy policy: `.../privacy/`
- Support / FAQ: `.../support/`
- Terms: `.../terms/`

## Custom domain later

Add a `CNAME` file containing the domain, set `baseurl: ""`, and point DNS per GitHub's docs.

## Local preview

```sh
gem install jekyll && jekyll serve
```
