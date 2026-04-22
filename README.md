# Core Judo — juhsu.github.io

Static business site for Core Judo, San Mateo CA.

## Deploy to GitHub Pages

1. Create a repo named **`juhsu.github.io`** at github.com/new
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/juhsu/juhsu.github.io.git
   git push -u origin main
   ```
3. In the repo → **Settings → Pages → Source**: `Deploy from branch` → `main` / `/ (root)`
4. Site goes live at **https://juhsu.github.io** within ~1 minute

## Updating content

All content is in `index.html`. Common things to swap:
- **Phone / email** — search `(650) 000-0000` and `info@corejudo.com`
- **Schedule** — edit the `<tbody>` rows in the `#schedule` section
- **Class descriptions** — edit text inside `.class-card` elements
- **Map** — replace the Google Maps `src` iframe URL with a fresh embed from maps.google.com
