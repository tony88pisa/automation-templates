# GitHub Bounty Scanner Lite (free)

Every 6 hours: GitHub search for `label:bounty` open + unassigned + <3 days old → scores each issue (`reward×2 + freshness − comment-crowd×5`) → posts the top 5 as a Discord digest.

## Setup (2 min)

1. n8n → **Workflows → Import from File** → `workflow.json`
2. Set env var `DISCORD_WEBHOOK_URL` (Discord channel → Edit → Integrations → Webhooks)
3. Activate. Optional: add `GITHUB_TOKEN` to the HTTP node headers for higher rate limits.

## Upgrade

[Premium Bounty Radar ($29)](https://tonypisa.gumroad.com/l/bounty-radar-n8n): 5 sources (Algora, Polar, Opire, IssueHunt, Expensify), 16 nodes, dedup TTL, error alerts, Telegram + Google Sheets output.
