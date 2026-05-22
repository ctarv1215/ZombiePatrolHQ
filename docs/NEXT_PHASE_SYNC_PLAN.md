# Next Phase Sync Plan

After MVP visual approval, build two upgrade packages:

1. `ZombiePatrolHQ_SyncUpgrade`
   - Cloudflare D1 schema
   - Cloudflare Pages Function snapshot ingest endpoint
   - HMAC signature validation
   - R2 sanitized snapshot archive
   - Public data query helpers

2. `Annelle_2.2.0_PublicSync_DEV`
   - Public snapshot exporter
   - Forbidden-field scanner
   - Signed outbound HTTPS upload client
   - Local snapshot archive
   - Once-per-hour Task Scheduler helper

Annelle remains local/LAN-only. The cloud website receives only sanitized, public-safe snapshots.
