# Nikhil K — Portfolio

Personal portfolio website. A single static page: no build step, no dependencies, no API keys.

## Edit your content

Open `index.html` and find the `SITE` object near the bottom of the file. Everything (text, links, projects, skills, education, activities) is edited there.

## Replace the placeholders

| What | Where | How |
| --- | --- | --- |
| Profile photo | `assets/` | Add `profile.jpg`, then set `photo: "assets/profile.jpg"` in `SITE` |
| Project images | `assets/projects/` | Add images, then set `image: "assets/projects/medfinder.jpg"` on each project |
| Resume | `assets/resume.pdf` | Replace the placeholder PDF, keeping the same file name |

Tip: resize photos to about 1200 px wide and compress them (squoosh.app) so the site loads fast.

## Run locally

Open `index.html` in a browser, or run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## Deploy with GitHub Pages

1. Create a new repository on GitHub (for example `knikhil4327.github.io` for a root URL, or `portfolio`).
2. Upload all files from this folder (or use Git below).
3. Go to Settings > Pages, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
4. Your site goes live in a minute or two.

```bash
git init
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/knikhil4327/portfolio.git
git push -u origin main
```

Netlify Drop and Vercel also work: just drag the folder in.
