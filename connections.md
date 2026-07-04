# Connections

Registry of every system your AIOS can reach. Filled by `/onboard` from Q4-Q7 answers; expanded over time as you wire new tools. `/audit` checks this file for domain coverage and freshness.

| # | Domain | Tool | Mechanism | Auth | Last checked |
|---|---|---|---|---|---|
| 1 | Revenue / Financials | Revolut Business (moving to Zoho Books) | not yet connected | — | — |
| 2 | Customer interactions | Gmail | not yet connected | — | — |
| 3 | Calendar | Google Calendar (inferred from Gmail) | not yet connected | — | — |
| 4 | Communication | Gmail | not yet connected | — | — |
| 5 | Project / task tracking | Custom database + dashboard (Flairr-built) | not yet connected | — | — |
| 6 | Meeting intelligence | Fireflies | not yet connected | — | — |
| 7 | Knowledge / files | — | not yet connected | — | — |

**Mechanism options:** `mcp` (MCP server), `script` (Python/Bash hitting an API, in `scripts/`), `export` (CSV/JSON dump pipeline), `key+ref` (`.env` key + `references/{tool}-api.md` guide), `not yet connected`.

When you wire a new tool, also save `references/{tool}-api.md` capturing endpoints, auth flow, and common queries — researched-once-saved-forever.
