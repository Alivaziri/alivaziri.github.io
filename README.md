# Ali Vaziri — portfolio

Static HTML, CSS, and JavaScript, published with GitHub Pages. No production build is required.

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

For a live-reloading preview (including the supervised visual review environment):

```bash
npm ci
npm run dev
```

Vite is used only for local preview. GitHub Pages continues to serve the root HTML files directly.

## Content

- `index.html`: introduction and selected results.
- `projects.html`: project descriptions, figures, and result animations.
- `experience.html`: industry experience, research, education, and skills.
- `publications.html`: publication metadata and existing paper/code links.
- `certifications.html`: reinforcement learning certificate.
- `assets/CV.pdf`: downloadable CV.

Reported comparisons retain the conditions and baselines from the supplied résumé. Publication titles, authors, statuses, and links are preserved from the existing website.
