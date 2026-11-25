# shainsethi.github.io

Personal site of Shain Sethi. One hand-written `index.html`, no framework, no build step.

## Deploy (GitHub Pages)

1. On GitHub, signed in as **shainsethi**, create a public repo named exactly `shainsethi.github.io`.
2. From this folder:
   ```bash
   git init -b main
   git add .
   git commit -m "New portfolio"
   git remote add origin https://github.com/shainsethi/shainsethi.github.io.git
   git push -u origin main
   ```
3. Repo Settings > Pages: Source "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Live in a minute or two at https://shainsethi.github.io/

## To do

- Project screenshots: add `assets/oil-dashboard.png` and `assets/flowforge.png` (1280x800) and put an `<img>` back at the top of each project card.
- Resume: add `assets/resume.pdf` and a "Resume" button in the hero, if you want one public.
