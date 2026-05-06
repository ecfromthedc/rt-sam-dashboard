# Sam's Morning Dashboard

Daily click-through dashboard for the scraper → Cobrand → Tides Tracker workflow at Rising Tides.

**Live URL:** https://ecfromthedc.github.io/rt-sam-dashboard/

## What it is
A single-page workspace for Sam (Campaign Assistant) to run the morning scraper routine. Auto-detects today's day of the week and surfaces the right steps:
- Mon/Tue/Thu — daily scrape only
- Mon/Wed/Fri — daily scrape + Tides Tracker + label sheet sync
- Sat/Sun — no scrape

Every step has clickable links straight to the tools (Campaign Hub, Notion CRM, Cobrand, Warner / AMG / Empire sheets) so Sam can move through the workflow without hunting for tabs.

## Inline prompt bible
Steps 1, 3, 4, 5, and 7 each have an expandable "Stuck? Use this prompt" block with copy-paste-ready Claude prompts. Designed for use in a Cursor session pointed at the `risingtides-campaign-hub` repo, but they work in plain Claude chat too — just paste the relevant campaign data manually first.

Variables in `[BRACKETS]` are highlighted in violet; replace with values from Campaign Hub before sending. Click the **Copy** button on any prompt block to copy the full text to your clipboard.

Source content for the prompts: `~/Documents/Obsidian Vault/Rising Tides OS/Session Logs/2026-05/session-2026-05-06/scraper-workflow/03-PROMPT-BIBLE.md`

## Source of truth
The full workflow SOP lives in the Rising Tides Obsidian vault:
`~/Documents/Obsidian Vault/Rising Tides OS/SOPs/Scraper-Workflow.md`

Update this dashboard whenever the SOP changes — they should stay in sync.

## Hosting
Static HTML hosted on GitHub Pages from `main`. Edit `index.html` → push → live within a minute.
