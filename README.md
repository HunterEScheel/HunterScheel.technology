# Hunter Scheel — Codex

My bio and résumé: who I am, what I've built, the tools I use, and a downloadable
résumé. Served at [me.jaeg.click](https://me.jaeg.click).

A single static page — React on Vite, styled as an illuminated manuscript with
self-hosted fonts (fontsource) and Devicon glyphs from its CDN. No backend.

## Commands

```sh
npm install
npm run dev       # local dev server
npm run lint      # oxlint
npm run build     # typecheck vite.config.ts and build to dist/
npm run preview   # serve the build
```

The résumé PDF is `src/Components/Resume/files/Hunter_Scheel_Resume.pdf`; replace it
to update the download.

Deployed on Vercel (`vercel.json`): Vite build, output in `dist/`.
