# Automation Templates — Free n8n Workflows, SVG Patterns & Dev Datasets

Free, production-tested automation assets built and used daily by a real autonomous agent system (Jarvis Studio). Everything here works out of the box — import, set one env var, run.

**Premium versions** (multi-source scoring, dedup, error routing, full packs) live on [Gumroad → tonypisa.gumroad.com](https://tonypisa.gumroad.com).

## 🆓 Free n8n Workflows

| Workflow | What it does | Setup |
|---|---|---|
| [`github-bounty-scanner-lite`](n8n-workflows/github-bounty-scanner-lite/) | Every 6h searches GitHub for fresh **unassigned bounty issues ≥$50**, scores by reward + freshness − crowd, posts top-5 digest to Discord | `DISCORD_WEBHOOK_URL` |
| [`hn-digest`](n8n-workflows/hn-digest/) | Daily 8AM digest of Hacker News top 10 (score + links) to Discord | `DISCORD_WEBHOOK_URL` |

Import: n8n → *Workflows → Import from File* → pick `workflow.json` → set env var → activate.

## 🎨 Free SVG Seamless Patterns

4 MIT-licensed geometric patterns in [`svg-patterns/free-samples`](svg-patterns/free-samples/) — tileable, print-ready, Cricut/sublimation-safe. The full pack (48 patterns, 6 families × 8 colorways) is [€19 on Gumroad](https://tonypisa.gumroad.com).

## 💎 Premium Versions

| Product | Price | What the paid version adds |
|---|---|---|
| [Bounty Radar n8n](https://tonypisa.gumroad.com/l/bounty-radar-n8n) | $29 | 16 nodes, **5 bounty sources** (Algora, Polar, Opire, IssueHunt, Expensify), ROI scoring, dedup with 30-day TTL, error-trigger admin alerts, Telegram + Sheets dual output |
| [PR Bot n8n](https://tonypisa.gumroad.com/l/pr-bot-n8n) | $79 | Auto-drafts PR proposals on bounty issues, tracks lifecycle, healing loop |
| [Protocol Radar Dataset](https://tonypisa.gumroad.com/l/protocol-radar-dataset) | $49 | Curated agent/bounty platform dataset — sources, fees, payout rails, verdicts |
| [Solver Trajectory Pack](https://tonypisa.gumroad.com/l/solver-trajectory-pack) | $99 | Real agent solver sessions (success+failure traces) for eval/fine-tuning |

## Why free?

These workflows run in production inside our own system. Free versions prove the quality — if the lite scanner saves you 20 minutes, the paid one saves you 18 hours a month.

Issues/requests welcome. ⭐ the repo if a workflow lands you a bounty.
