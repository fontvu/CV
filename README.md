# CV — Phong Vu

Static CV/resume website for **Phong Vu**, IT Security Engineer. Built with vanilla HTML & CSS and deployed to GitHub Pages via GitHub Actions.

## 🌐 Live

**[https://fontvu.github.io/CV/](https://fontvu.github.io/CV/)**

## Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5, semantic elements |
| Styling | Vanilla CSS (Dracula theme) |
| Icons | Font Awesome 6 |
| Font | Inter (Google Fonts) |
| CI/CD | GitHub Actions |
| Hosting | GitHub Pages |

## Development

Open locally:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deployment

Deployments happen automatically on push to `main` via the GitHub Actions workflow in `.github/workflows/deploy.yml`.

To trigger manually: go to **Actions → Deploy CV to GitHub Pages → Run workflow**.

## Files

```
.
├── index.html                        # CV website
├── style.css                         # Dracula-inspired dark theme
├── cv.tex                            # LaTeX source (Overleaf)
├── .github/workflows/deploy.yml      # GitHub Pages deployment
└── .gitignore
```

## License

© Phong Vu. All rights reserved.
