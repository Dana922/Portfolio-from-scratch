# Dana Product Design Portfolio

Step 1 establishes the Astro project, shared layout, navigation, footer,
responsive design tokens, metadata, and an accessible homepage shell.

## Run locally

```bash
npm install
npm run dev
```

Astro will print the local address in the terminal.

## Create a production build

```bash
npm run build
```

The deployable static website is generated in `dist/`.

## Cloudflare Pages settings

- Framework preset: Astro
- Build command: `npm run build`
- Build output directory: `dist`
- Root directory: `/`
- Node.js version: 22

Connect the GitHub repository in Cloudflare Pages. Each push to the selected
production branch will trigger a new deployment.
