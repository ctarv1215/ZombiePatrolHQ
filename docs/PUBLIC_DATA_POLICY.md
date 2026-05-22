# Public Data Policy - MVP v0.1

This website is public and has no authentication in this phase. Therefore, it may display only public-safe training data.

## Allowed in MVP

- Callsign
- Avatar
- Custom background
- Team name/logo
- Rank
- Public medals
- Public recognition tiers/icons
- Public aggregate stats
- Public leaderboard placement
- Public game/session summaries
- Public facility map/lore content

## Excluded in MVP

- Phone numbers
- Emails
- Full legal names
- Birthdays
- Addresses
- Verification values
- PINs or password hashes
- AppUser records
- Service Record claim data
- Data Health issues/actions
- Identity evidence
- AlphaTag Client Base raw records
- AlphaTag DB snapshots
- Raw AlphaTag JSON
- Staff/Admin users
- Deployment settings
- Local paths/IPs
- Logs/backups
- Write-back queue data

## Network principle

The public website must not connect public visitors to the Annelle Host PC, AlphaTag hardware/software, or Lake Area Adventures internal systems. The later sync phase should use outbound-only signed snapshot upload from Annelle to Cloudflare.
