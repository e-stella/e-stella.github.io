# e-stella.github.io

Personal site for [@e-stella](https://github.com/e-stella), hosted on [GitHub Pages](https://pages.github.com/).

## Preview locally

```bash
cd /Users/eskoh/Documents/my-website
python3 -m http.server 8000
```

Visit http://localhost:8000

## Publish to GitHub

1. Create a new repo at [github.com/new](https://github.com/new) named **`e-stella.github.io`** (this gives you the clean URL below).
2. Leave it empty — do not add a README.
3. Push:

```bash
cd /Users/eskoh/Documents/my-website
git remote add origin https://github.com/e-stella/e-stella.github.io.git
git branch -M main
git push -u origin main
```

4. **Settings → Pages** → deploy from branch **`main`**, folder **`/ (root)`**.
5. Your site will be live at **https://e-stella.github.io**

If you use a different repo name (e.g. `my-website`), the URL is `https://e-stella.github.io/my-website/` instead.

## Edit the site

- `index.html` — content
- `styles.css` — design

```bash
git add .
git commit -m "Update site"
git push
```
