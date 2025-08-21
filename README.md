# Travis Lelle — Astro + Netlify Starter

Features:
- Dark, minimalist theme
- Landing page with affiliate buttons
- Mini‑blog (Markdown posts)
- Canvas minigame (Snake)
- Netlify-ready (including a simple contact form)

## Quick start
1. Install Node 18+.
2. `npm install`
3. `npm run dev` (http://localhost:4321)
4. Edit affiliate URLs in `src/pages/index.astro`.
5. Deploy to Netlify (link your GitHub repo).

### Deploying
- Push this folder to a new GitHub repo.
- In Netlify, 'New site from Git' → select repo.
- Build command: `npm run build`
- Publish directory: `dist`
- Add your custom domain in Netlify → DNS → SSL.

### Blog posts
- Add Markdown files to `src/pages/blog/` (frontmatter supported).

### Customize
- Colors/spacing live in `public/styles.css`.
- Navigation/layout in `src/layouts/Layout.astro`.
- Game logic in `src/pages/fun.astro`.

### Notes
- Remember to include an affiliate disclosure (already in footer).
- Replace `site` in `astro.config.mjs` with your actual domain.
