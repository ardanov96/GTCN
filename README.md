# GLITCHICONS — Landing Page

> Official landing page for [GLITCHICONS](https://github.com/ardanov96/glitchicons) — AI-Powered Security Research Platform

**Live:** https://ardanov96.github.io/GTCN/

---

## About

This repository hosts the static landing page for the Glitchicons security platform, served via GitHub Pages.

## Stack

- Pure HTML + CSS + Vanilla JS — no framework, no build step
- Self-contained single file (`index.html`)
- Hosted via GitHub Pages (branch: `master`)

## Structure

```
GTCN/
├── index.html        # Main landing page
├── style.css         # Dark theme stylesheet
├── glitchicons.png   # Logo
├── og-preview.png    # Social media preview
├── robots.txt
└── sitemap.xml
```

## Features

- Loading screen + attack canvas animation
- Custom cursor + spark effects
- Scroll reveal animations
- Interactive capabilities section (5-tab slider)
- Geo-based pricing (USD / IDR)
- Responsive mobile layout

## Current Version

**v2.0.0** — reflecting Glitchicons platform:
- 1083 unit tests · 0 failures
- 6 Go binaries (glitchrace, glitchscan, glitchfuzz, glitchdns, glitchtls, glitchproxy)
- 28 attack modules
- Web Dashboard (FastAPI + SSE)
- Multi-Target Orchestrator
- Cloud Security (S3/Azure/GCP/IMDS)
- Auth Expansion (SAML/PKCE/SSO/API Key)

## Deploy

Push to `master` — GitHub Pages deploys automatically.

```bash
git add index.html style.css
git commit -m "update: ..."
git push
```

## Links

- Platform repo: https://github.com/ardanov96/glitchicons
- Live site: https://ardanov96.github.io/GTCN/
- Contact: ardanov96@gmail.com

---

MIT License © 2026 GLITCHICONS
