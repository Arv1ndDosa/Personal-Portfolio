# Arvind Srinivasan — Portfolio

My personal portfolio site: projects, experience, resume, and contact info.

Live at: https://YOUR-GITHUB-USERNAME.github.io

## Files

- `index.html` — the whole site (HTML + CSS in one file)
- `resume.pdf` — linked from the Resume button

## Editing

- Replace every `YOUR-GITHUB-USERNAME` in `index.html` with your GitHub username.
- Each project has a "View code" link. Swap in the real repo URL, or delete the line.
  Any link still containing `YOUR-` is hidden automatically on the live site.
- To update the resume, replace `resume.pdf` with a new file of the same name.

## Deploying with GitHub Pages

1. Create a new public repo named exactly `YOUR-GITHUB-USERNAME.github.io`.
2. Upload `index.html`, `resume.pdf`, and this `README.md` to the repo
   (on github.com: Add file → Upload files → Commit).
3. Go to Settings → Pages. Under "Build and deployment", set Source to
   "Deploy from a branch", pick `main` and `/ (root)`, and save.
4. Wait a minute or two, then visit `https://YOUR-GITHUB-USERNAME.github.io`.

Or from the command line:

```bash
cd portfolio
git init
git add .
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/YOUR-GITHUB-USERNAME.github.io.git
git push -u origin main
```

After that, every push to `main` updates the live site.
