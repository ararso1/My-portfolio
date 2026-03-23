# Portfolio — Ararso Alisho

Live site: [ararso.vercel.app](https://ararso.vercel.app/)

## Develop

The live site files live in `_site/`. To preview locally:

```bash
npx serve _site
```

Or any static file server pointed at the `_site` folder.

The `_includes/layouts/` templates are for Eleventy if you add Markdown or Nunjucks pages later; the homepage is currently edited directly as `_site/index.html`.

## npm scripts

`npm start` / `npm run build` run Eleventy with the repo defaults. If you add `.eleventy.js` and source templates at the project root, you can wire a proper build; until then, prefer serving `_site` directly.
