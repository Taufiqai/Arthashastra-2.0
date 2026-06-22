# Arthashastra 2.0

### Sutras for Bangladesh in the Age of Artificial Intelligence

*as if Kautilya were advising a modern State shaped by rivers, a large population, and digital ambition*

**Md Taufiqul Islam** — Joint Secretary, Cabinet Division, Government of Bangladesh

---

This repository hosts the companion web experience for the book *Arthashastra 2.0*, applying the analytical method of classical statecraft to the governance of artificial intelligence in Bangladesh. Thirty original sutras, ten chapters of scholarship, and a complete interactive analytical toolkit.

## What's here

| File | Description |
|------|-------------|
| `index.html` | **Combined homepage** — the landing page linking to both portals, with downloads and author sections |
| `book.html` | **The Immersive Book Portal** — chapters, sutras, post-impressionist artwork, animated visualisations, strategic roadmap |
| `lab.html` | **The Sutra Analytics Lab** — per-sutra governance scores, indicators, actions; an interactive strategy quadrant; and a live institutional self-assessment engine |
| `dashboard.html` | **The Fiscal–Monetary Interface Simulator** — an interactive FY27 policy model: adjust the pay scale, deficit, and financing mix and watch inflation, the policy rate, and private credit respond |
| `downloads/` | The full book in illustrated PDF, the Analytical Companion PDF, the diagram-edition PDF, and the editable DOCX manuscript |

## Live site

Once deployed via GitHub Pages, the site is served from the repository root, with `index.html` as the entry point.

## Local preview

No build step is required — these are static files. To preview locally:

```bash
# from the repository root
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

This repository includes a GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically publishes the site to **GitHub Pages** on every push to the `main` branch.

To enable it once:

1. Go to the repository's **Settings → Pages**.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Push to `main` — the workflow deploys automatically.

Your site will be available at `https://<username>.github.io/Arthashastra-2.0/`.

> The homepage and portals use **relative links** (`book.html`, `lab.html`, `downloads/…`), so they work correctly both at a domain root and under a project-pages sub-path.

## Credits & rights

All text, artwork, and analytical frameworks © 2026 Md Taufiqul Islam. The post-impressionist artwork is generated algorithmically and original; no copyrighted images are reproduced. Scholarly citations refer to peer-reviewed publications, listed in full within the book.

---

> *"He who commands armies rules the present. He who commands data rules the future. He who commands trust rules forever."*
