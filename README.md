# Sam's Morning Dashboard

Daily click-through dashboard for the scraper → Cobrand → Tides Tracker workflow at Rising Tides.

**Live URL:** https://ecfromthedc.github.io/rt-sam-dashboard/

## What it is
A single-page workspace for Sam (Campaign Assistant) to run the morning scraper routine. Auto-detects today's day of the week and surfaces the right steps:
- Mon/Tue/Thu — daily scrape only
- Mon/Wed/Fri — daily scrape + Tides Tracker + label sheet sync
- Sat/Sun — no scrape

Every step has clickable links straight to the tools (Campaign Hub, Notion CRM, Cobrand, Warner / AMG / Empire sheets) so Sam can move through the workflow without hunting for tabs.

## Source of truth
The full workflow SOP lives in the Rising Tides Obsidian vault:
`~/Documents/Obsidian Vault/Rising Tides OS/SOPs/Scraper-Workflow.md`

Update this dashboard whenever the SOP changes — they should stay in sync.

## Hosting
Static HTML hosted on GitHub Pages from `main`. Edit `index.html` → push → live within a minute.
