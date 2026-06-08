# Arghya Roy Portfolio

Static single-page portfolio site for Arghya Ranjan Roy, an AI automation engineer focused on workflow automation, RAG systems, and AI integration audits.

## Stack

- HTML
- CSS
- Vanilla JavaScript
- Google Fonts

No framework, backend, chatbot, API key, or build tooling is required.

## Repository Structure

```text
.
├── index.html
├── README.md
├── .gitignore
├── .github/
│   └── workflows/
│       └── deploy-pages.yml
├── assets/
│   ├── images/
│   └── downloads/
├── docs/
│   └── plans/
├── case-studies/
└── architectures/
```

## Run Locally

Open `index.html` directly in a browser.

## Push To GitHub

```bash
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

## Deploy With GitHub Pages

This repo includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`.

After pushing to GitHub:

1. Open the repository on GitHub.
2. Go to `Settings > Pages`.
3. Set `Source` to `GitHub Actions`.
4. Push to `main` to trigger deployment.

## Notes

The Calendly booking link is currently represented by a placeholder. Until the real link is added, the site uses `mailto:arghyaroy1999@gmail.com` as the primary fallback contact path.
