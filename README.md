# Convex Hedge — Landing Page Bundle

## How to run locally

### Option A — Python (no install needed)
```
cd convex-hedge-bundle
python -m http.server 8000
```
Then open: http://localhost:8000/

### Option B — VS Code Live Server
Open the folder in VS Code and click "Go Live"

### Option C — Double-click
Open index.html directly in Chrome or Edge (most features work without a server)

## Structure
```
convex-hedge-bundle/
├── index.html          ← Main page (fully self-contained)
├── fonts/
│   ├── PPNeueMachina-PlainRegular.otf
│   └── PPNeueMachina-PlainUltrabold.otf
└── assets/
    ├── tailwind.js     ← Tailwind CSS (offline copy)
    ├── fonts.css       ← Google Fonts CSS (offline)
    └── *.woff2         ← Inter + JetBrains Mono font files
```

## No internet connection required after bundling.
