# Personal website

A simple 3-file static site: `index.html`, `style.css`, `script.js`. No build step needed.

## Put it on GitHub Pages

1. Create a new repo on GitHub, e.g. `aneesh-miryala.github.io` (using this exact name gets you the site at `https://aneesh-miryala.github.io` with no extra config — or use any repo name and enable Pages below).
2. Upload these three files to the repo (drag-and-drop on github.com works, or use `git`):
   ```
   git init
   git add index.html style.css script.js README.md
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
5. Wait a minute, then visit the URL GitHub shows you (either `https://YOUR-USERNAME.github.io/YOUR-REPO` or `https://aneesh-miryala.github.io` if you used the special repo name).

## Before you publish, personalize

- Swap the three placeholder project sheets in `index.html` for real projects (title, description, tags, link).
- Replace the "About" paragraphs with your own.
- Replace `you@example.com` with your real email.
- Your Instagram, LinkedIn, and TikTok links are already wired up in the "Find me elsewhere" section.

## Design notes

Blueprint / drafting-sheet theme — navy background, warm paper/chalk text, hairline rules, corner tick marks on project "sheets," single amber accent. Fonts: Fraunces (display), Inter (body), JetBrains Mono (small labels). Fully responsive and keyboard-accessible.
