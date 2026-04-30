# PROVIDENTIA — Projection Slides

Kinetic HTML projection system. 17 slides. No framework, no build step.

## Quick Start

```bash
npm install
npm start
# → http://localhost:3000
```

## Repo Structure

```
providentia-projection/
├── public/
│   └── index.html        # All slides — self-contained, logos embedded as base64
├── package.json
├── .gitignore
├── netlify.toml          # Netlify deploy config
├── vercel.json           # Vercel deploy config
└── README.md
```

## Deploy

### Netlify
Push to GitHub, connect repo in Netlify dashboard.
- Build command: _(leave blank)_
- Publish directory: `public`

Or via CLI:
```bash
npx netlify-cli deploy --dir public --prod
```

### Vercel
```bash
npx vercel --yes
```

### GitHub Pages
```bash
# In repo Settings → Pages → Source: Deploy from branch
# Branch: main  /  Folder: /public
```

### Railway / Render
- Start command: `npm start`
- Build command: `npm install`
- Port: `3000`

## Controls

| Input | Action |
|---|---|
| `→` or `Space` | Next slide |
| `←` | Previous slide |
| Click nav dots | Jump to slide |
| Swipe | Mobile navigation |
