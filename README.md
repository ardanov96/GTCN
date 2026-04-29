# GLITCHICONS ⬡
> **Decepticons Siege Division** — AI-Powered Fuzzing Intelligence

Landing page for Glitchicons — open-source offensive fuzzing toolkit.

## Structure
```
glitchicons/
├── index.html        ← Single page, English, geo-adaptive pricing
├── glitchicons.png   ← Logo (standalone)
├── .nojekyll         ← Required for GitHub Pages
└── README.md
```

## Deploy → GitHub Pages
1. New repo → Public → upload files
2. Settings → Pages → Branch: main / root → Save
3. Live at: `https://[username].github.io/glitchicons/`

## Pricing Logic
- Visitor from **Indonesia (ID)** → IDR shown first, USD secondary
- All other countries → USD shown first, IDR secondary
- Detection: `ipapi.co` (free, no API key, <1s latency)
- Fallback on timeout: USD (default)

## License
MIT © 2025 ARDATRON
