# MBASA Website

Bright, vibrant, presentation-ready site for MBASA.

## Local dev

```bash
cd web
nvm use 22
npm install
npm run dev -- --host 127.0.0.1 --port 5173
```

## Build

```bash
cd web
nvm use 22
npm run build
npm run preview
```

## Deploy (Vercel)

- **Framework**: Astro
- **Build command**: `npm run build`
- **Output directory**: `dist`

Config is included in `web/vercel.json`.
