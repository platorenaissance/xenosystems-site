# XENOSYSTEMS

A constitutional project for a new monetary sovereign.

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the GitHub repository
4. Click **Deploy** — no configuration needed

Vercel will automatically detect the `vercel.json` and serve the `public/` directory.

## Local Development

Just open `public/index.html` in a browser. No build step required.

Or use any static server:

```bash
npx serve public
```

## Interactions

- **Click** — data burst ripple
- **Click + drag** — orbit/rotate the 3D scene
- **Scroll wheel** — zoom in/out through layers
- **Mouse movement** — parallax + velocity affects scroll speed
- **Space** — massive data burst
- **Enter** — cycle speed (normal → 3× → 0.2× → normal)
- **Arrow keys** — manual rotation
- **R** — reset view
- **Touch drag** — rotate (mobile)
- **Pinch** — zoom (mobile)
- **Tap** — data burst (mobile)

## Structure

```
├── public/
│   ├── index.html          # Full application (single file)
│   ├── favicon.ico          # ICO favicon
│   ├── favicon.svg          # SVG favicon
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon-180x180.png  # Apple touch icon
│   ├── favicon-192x192.png  # Android icon
│   ├── favicon-512x512.png  # Large icon
│   ├── manifest.json        # PWA manifest
│   └── robots.txt
├── vercel.json              # Vercel deployment config
├── .gitignore
└── README.md
```
