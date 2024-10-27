# SvelteKit Fonts Examples

This is a project to demonstrate how to use fonts in SvelteKit.

Two examples are provided:

1. Using Google Fonts via the `@fontsource` package
2. Using a local font (ttf, woff2, etc)

## Getting Started

First, run the development server:

```bash
nvm use # or use Node 22
npm i
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) with your browser to see the result.

## Preloading

To preload fonts, we use the `preload` option in `handle` in `src/hooks.server.ts`. This makes sure all font files are preloaded via `<link rel="preload">` tags in the `<head>`.

## Prod build with adapter-node

```bash
npm run build
node build/index
```
