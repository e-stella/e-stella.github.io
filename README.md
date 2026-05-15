# My website

A simple personal site hosted on [GitHub Pages](https://pages.github.com/) — free with any GitHub account.

## Preview locally

Open `index.html` in your browser, or run:

```bash
cd /Users/eskoh/Documents/my-website
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Publish to GitHub

1. Sign in at [github.com](https://github.com).
2. Click **+** → **New repository**.
3. Name it `my-website` (or any name you like).
4. Leave it empty (no README) — this folder already has files.
5. In Terminal, from this folder:

```bash
git remote add origin https://github.com/YOUR_USERNAME/my-website.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

6. On GitHub: **Settings** → **Pages** → **Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `/ (root)`
7. Save. After 1–2 minutes your site is live at:

   `https://YOUR_USERNAME.github.io/my-website/`

## Optional: custom URL at username.github.io

Rename the repo to `YOUR_USERNAME.github.io` (exactly your username). Then the site URL is:

`https://YOUR_USERNAME.github.io`

## Edit the site

- `index.html` — content and structure
- `styles.css` — colors, fonts, layout

Push changes with `git add .`, `git commit -m "Update site"`, `git push`.
