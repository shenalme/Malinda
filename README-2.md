# Malinda Perera — Portfolio Site

A single-page site, ready to host on GitHub Pages.

## Deploy in 5 minutes

1. **Create a repository** on GitHub (e.g. `malinda-perera`). Public repos get free Pages hosting.
2. **Add `index.html`** (this file) to the root of the repo — either drag-and-drop it in the GitHub web UI, or via command line:
   ```bash
   git init
   git add index.html
   git commit -m "Add site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
   ```
3. **Turn on Pages**: in the repo, go to **Settings → Pages**. Under "Build and deployment," set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
4. Wait a minute, then your site is live at:
   ```
   https://YOUR-USERNAME.github.io/YOUR-REPO/
   ```
   If the repo is named `YOUR-USERNAME.github.io`, it'll be live at `https://YOUR-USERNAME.github.io/` directly.

## Notes

- Everything (HTML, CSS, JS) is in the one `index.html` file — no build step, no dependencies to install.
- It pulls fonts from Google Fonts over CDN, so an internet connection is needed to see the intended typography.
- The photo area is a placeholder plate — swap it for a real image by editing the `.plate` div and adding an `<img>` tag, then upload the image file alongside `index.html` in the repo.
- The double-check flagged earlier still stands: verify the IMDb link and filmography match before this goes fully public.
