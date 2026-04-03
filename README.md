# Invertible Matrix Interactive

Vite + React SPA for **3×3** matrix pairs: check whether two matrices are inverses (identity product) with bracket UI and predefined examples.

**Live:** served under GitHub Pages with `base: '/invertible-matrix/'` (e.g. `https://content-interactives.github.io/invertible-matrix/`).

## Stack

- React 19, Vite 6
- Tailwind CSS 3, PostCSS
- Lucide React
- `gh-pages`

## Setup

```bash
npm install
npm run dev
```

## Scripts

| Command | Description |
|--------|-------------|
| `npm run dev` | Dev server |
| `npm run build` | Production build |
| `npm run preview` | Preview `dist/` |
| `npm run lint` | ESLint |
| `npm run deploy` | Build + GitHub Pages |

## Layout

- `src/App.jsx` — mounts `InvertibleMatrix`
- `src/components/InvertibleMatrix.jsx` — matrix UI and logic

## Configuration

`vite.config.js`: `base: '/invertible-matrix/'`.
