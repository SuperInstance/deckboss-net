# DeckBoss

> Fleet operations management for commercial fishing.

**[deckboss.net](https://deckboss.net)**

DeckBoss handles vessel tracking, fuel monitoring, crew scheduling, maintenance logs, and delivery reconciliation for commercial fishing fleets. Built to work where cell signal doesn't — offline-first, wheelhouse-ready.

## What It Does

- **Vessel positioning** — GPS logging, trip tracks, speed/position history
- **Fuel tracking** — Burn rate per hour/trip, refuel logs, range remaining
- **Crew management** — Aboard lists, crew hours, lay shares, settlement sheets
- **Maintenance scheduling** — Engine hours, haul-out dates, inspection deadlines
- **Delivery reconciliation** — Match catch logs to buyer tickets, flag discrepancies
- **Offline everything** — Full functionality without connectivity

## Tech Stack

- Cloudflare Workers (edge deployment)
- Single-file HTML response served from the worker
- Custom domain via Cloudflare

## Deployment

```bash
npx wrangler deploy
```

## Part of [SuperInstance](https://superinstance.ai)

DeckBoss is one of the SuperInstance suite of tools — purpose-built apps for people who do real work in real places.
