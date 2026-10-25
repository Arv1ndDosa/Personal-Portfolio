# Arvind Srinivasan — Portfolio

My personal portfolio site: projects, experience, resume, and contact info.

Live at: https://arvind-srinivasan.vercel.app

## Files

- `index.html` — the whole site (HTML + CSS in one file)
- `resume.pdf` — linked from the Resume button

## Editing

- Each project has a "View code" link. Replace `YOUR-REPO-NAME` with the real repo name, or delete the line.
  Any link still containing `YOUR-` is hidden automatically on the live site.
- To update the resume, replace `resume.pdf` with a new file of the same name.

## Deploying with Vercel

1. Push this folder to a GitHub repo (any name works, like `portfolio`):

```bash
git init
git add .
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/Arv1ndDosa/portfolio.git
git push -u origin main
```

2. On vercel.com, click Add New → Project and import the repo.
3. Set the project name to `arvind-srinivasan`, leave Framework Preset as "Other", and click Deploy.
4. The site goes live at `https://arvind-srinivasan.vercel.app`. To change the address later,
   go to the project's Settings → Domains.

Every push to `main` redeploys the site automatically.
