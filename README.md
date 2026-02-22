# UEFT Website – Deployment Guide

A modern, dark‑mode, single‑page website for presenting the Unified Entanglement Field Theory (UEFT) framework.

## Files

```
ueft-website/
├── index.html              # Main page
├── style.css               # Stylesheet
├── papers/                 # Paper source files
│   ├── ueft_2f_paper_v2.tex
│   ├── ueft2f_refs.bib
│   └── README.md
└── README.md (this file)
```

## Hosting Options

### 1. GitHub Pages (easiest, free)
- Create a new repository (e.g., `ueft-website`)
- Push these files to the `main` branch
- Go to Settings → Pages → Source: `main` branch, `/ (root)`
- Your site will be at `https://username.github.io/ueft-website`

### 2. Your own domain (via Hostinger VPS)
- Upload files to `/var/www/html/ueft` (or similar) on your VPS
- Configure nginx/Apache to serve the site
- Point your domain (e.g., `ueft‑research.com`) to the server IP

### 3. Cloudflare Tunnel (already set up)
- Place files in a directory served by the tunnel (currently `/data/.openclaw/workspace/login‑minimal/`)
- Update tunnel configuration to include this new path

### 4. Netlify / Vercel (drag‑and‑drop)
- Drag the `ueft-website` folder onto their dashboard
- Automatic HTTPS, global CDN

## Next Steps

1. **Compile the paper PDF** locally with `pdflatex` and place it in `papers/ueft_2f_paper_v2.pdf`
2. **Update the Zenodo link** once you have a DOI (replace `https://zenodo.org` in `index.html`)
3. **Add a GitHub repo link** if you create a repository for the paper
4. **Share the link** in physics forums, social media, and relevant communities

## Customization

- Edit `index.html` to update text, add more sections, or change links
- Edit `style.css` to adjust colors, fonts, or layout
- Add images (plots, diagrams) to an `images/` folder and reference them

## License

The website content is CC BY 4.0. Feel free to adapt it for your own projects.