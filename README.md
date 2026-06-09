# GLITCHICONS — Landing Page

> Official landing page for [GLITCHICONS](https://github.com/ardanov96/glitchicons) — AI-Powered Offensive Security Platform

**Live:** https://ardanov96.github.io/GTCN/

---

## About

This repository hosts the static landing page for the Glitchicons offensive security platform, served via GitHub Pages.

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

- Loading screen + attack canvas animation (network breach sequence)
- Custom cursor + spark effects on click
- Scroll reveal animations
- Interactive capabilities section (5-tab slider with pagination)
- Geo-based pricing (USD / IDR auto-detected)
- Responsive mobile layout

## Current Version

**v5.2.0** — reflecting Glitchicons platform:
- 1757 unit tests · 0 failures
- 34 Go binaries across 4 tiers
- 9 CVE verifiers (Log4Shell · Zerologon · BlueKeep · CitrixBleed · PAN-OS · more)
- Active Directory attack suite (Kerberos AS-REP roasting · LDAP AD dump)
- HTTP request smuggling (CL.TE · TE.CL · TE.TE · h2c)
- WAF bypass coverage tester
- SIEM detection coverage (MITRE ATT&CK simulation)
- Supply chain security (dependency confusion · typosquatting)
- Cloud security posture (AWS · Azure · GCP · CIS Benchmark)
- AI report generation (Anthropic · OpenAI · Ollama)

### Go Binary Tiers

| Tier | Count | Focus |
|------|-------|-------|
| Tier 1 — Foundation | 7 | Network speed: race/scan/fuzz/dns/tls/proxy |
| Tier 2 — Protocol Depth | 8 | SMB · SSH · RDP · LDAP · SNMP · FTP · VNC · WMI |
| Tier 3 — Offensive Ops | 15 | Brute · Kerberos · NTLM relay · Exploit · Pivot · IDS evasion |
| Tier 4 — Elite Assessment | 4 | WAF testing · SIEM coverage · Supply chain · Cloud posture |

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
