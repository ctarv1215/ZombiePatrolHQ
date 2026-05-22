# Zombie Patrol HQ MVP v0.1

Public-facing Zombie Patrol HQ website prototype for `ZombiePatrolHQ.com`.

This first package is intentionally static and uses a sanitized placeholder Annelle snapshot generated from the current seeded Annelle 2.2.0 user-test data. It does **not** include live Annelle sync, login, Staff/Admin tools, D1, R2, or any WAN connection back to the Annelle Host PC.

## Local development

```bash
npm install
npm run dev
```

## Cloudflare Pages

Recommended settings:

- Framework preset: Astro
- Build command: `npm run build`
- Build output directory: `dist`
- Production branch: `main`
- Preview branch: `dev`

## MVP navigation

- HQ Dashboard
- Zombie Patrol History
- Training Center Information
- AlphaTag Arsenal
- Training Records
- Leaderboards
- Mission Archive
- Schedule Deployment

## Safety posture

This build is public/read-only. It contains no player login, no Staff/Admin login, no write actions, and no direct connection to Annelle or AlphaTag.
