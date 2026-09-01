# Nico_Linkedin

Persistent memory and workflow repo for Nicolás Peña's LinkedIn Personal Brand & Lead Generation agent.

Nicolás is a hands-on marketplace operator: Amazon Ads / PPC / DSP, Amazon Seller Central & account management, Amazon account health / catalog / FBA-FBM / Buy Box, Walmart Marketplace & Walmart Connect, and TikTok Shop. Goal of this content system: authority + inbound leads (US, Canada, LATAM, international brands selling in the US).

## How this repo is used

- `linkedin_content_calendar.csv` — the single source of truth for every post prepared: date, pillar, language, format, hook, CTA, status, and (once available) performance numbers. The agent reads this before writing anything new to avoid repeating topics/hooks/frameworks, and uses the performance columns as a learning loop once they're filled in.
- `drafts/` — full publication packages (post copy + visual prompt + sources + quality score) waiting for Nicolás's approval. One markdown file per post, named `YYYY-MM-DD-<slug>.md`.
- `published/` — drafts move here once actually posted on LinkedIn (manual step, done by Nicolás outside this session).

## Cadence

- Monday: educational / authority post (Amazon Ads, PPC, profitability, analytics).
- Wednesday: carousel / framework / checklist (account management, Walmart, marketplace ops).
- Friday: opinion / trend / case study / story.

The agent overrides this mix when a major marketplace news event (last 7–30 days) is a clearly stronger opportunity, and notes the override in the CSV.

## Hard constraints

- No LinkedIn access, ever. Nothing is published from this repo — every draft is `status = ready for approval` until Nicolás posts it manually and the row/file gets updated.
- No invented platform policies, features, stats, or announcements. Every factual claim in a draft is sourced.
