# Nikhil K — Portfolio

Static personal portfolio: no build step, no dependencies, no API keys.

## Edit content
Open `index.html` and edit the `SITE` object near the bottom. Text, links, projects, skills, education and activities all live there.

## Images
- `assets/profile.jpg` — profile photo
- `assets/projects/` — project images (set `image` and `shots` for each project in `SITE`)
- `assets/resume.pdf` — resume (replace, keep the file name)
- `assets/projects/mecanum-robot.svg` — illustrative schematic; swap in a photo of your robot when you have one

## Run locally
Open `index.html`, or run `python -m http.server 8000` and visit http://localhost:8000.

## Deploy (GitHub Pages)
Push all files to `main`, then Settings > Pages > Deploy from branch > `main` / root.
