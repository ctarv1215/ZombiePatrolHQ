# Zombie Patrol HQ MVP v0.1 Deployment

## Recommended repository workflow

- GitHub repository: `ZombiePatrolHQ`
- `main` branch: production
- `dev` branch: preview/testing

## Cloudflare Pages settings

- Framework preset: Astro
- Build command: `npm run build`
- Build output directory: `dist`
- Production branch: `main`

## First deploy

1. Commit this package into the GitHub repository.
2. Create or connect a Cloudflare Pages project to the repository.
3. Use the settings above.
4. Deploy to the Cloudflare preview domain first.
5. After visual approval, attach `ZombiePatrolHQ.com`.

## Not included in this MVP

- D1 live public database
- R2 snapshot/media storage
- Annelle hourly sync
- Player login
- Staff/Admin login
- Any public connection to the Annelle Host PC

Those are planned for the next phase after this visual/static MVP is approved.
