# B Cellars Vineyard Map — GitHub Pages Quick Publish

## Instructions

### Option 1 — Deploy from root (simplest)
1. Create (or open) your GitHub repository.
2. Place these files in the **root** of your repo:
   - `index.html`
   - Rename `nojekyll.txt` to `.nojekyll`
3. Commit & push to `main`.
4. Go to **Settings → Pages**:
   - Select "Deploy from a branch".
   - Branch: `main`
   - Folder: `/ (root)`
5. Save and wait ~1–2 minutes for your Pages site to build.

### Option 2 — Deploy from /docs folder
1. Create a folder in your repo named `docs`.
2. Place `index.html` and rename `nojekyll.txt` to `.nojekyll` inside `docs`.
3. In **Settings → Pages**:
   - Select "Deploy from a branch".
   - Branch: `main`
   - Folder: `/docs`
4. Save and wait for your site to publish.

**Why `.nojekyll`?**
GitHub Pages defaults to using Jekyll for static site builds. This file disables Jekyll so that your HTML, CSS, and JS files are served as-is.
