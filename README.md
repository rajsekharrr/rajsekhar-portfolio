# Rajsekhar — Portfolio (Static)

A simple, modern single-page portfolio for **Rajsekhar Singha Roy**. Built with HTML + Tailwind CDN and a tiny bit of JavaScript. No build step needed.

## Edit Your Info
- Open `site.config.json` and update:
  - `links.github` → your GitHub profile URL
  - `links.linkedin` → your LinkedIn URL
  - `resume_pdf` → optional direct link to your resume (else the **Download Resume** button opens the print dialog)
- Update `projects.json` with your projects (or keep the placeholders).

## Run Locally
Just open `index.html` in your browser. (For some browsers, you may need to use a static server to load JSON files. If you see CORS issues, run a tiny server:)

```bash
# Python 3
python -m http.server 5173
# then open http://localhost:5173
```

## Deploy Options
### GitHub Pages (no backend)
1. Create a new repo (e.g., `rajsekhar-portfolio`) and push these files.
2. In **Settings → Pages**, choose **Deploy from branch**, root folder, branch `main`. Save.
3. Your site will be live at `https://<your-username>.github.io/rajsekhar-portfolio/`.

### Netlify
- Drag‑drop this folder into https://app.netlify.com/drop or connect your repo. No build command needed.

### Vercel
- Import the repo on https://vercel.com/new. Set **Framework Preset** to **Other** (no build command). Output directory is `/`.

## Custom Domain
- Point your domain’s DNS to your hosting provider and set the site to use it (Netlify/Vercel have one‑click domain management).

## License
MIT — do anything, just keep the attribution.