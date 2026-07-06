# Code Dashboard — Mar 24

A single-page, static HTML "mission control" snapshot of Dave's personal dev portfolio: active projects, blocked decisions, machine fleet status, risks, and open threads, as of late March 2026.

This is a personal ops dashboard, not an end-user product. It's a hand-maintained (and later agent-updated) snapshot page — there is no build step, backend, or database; all data is hardcoded into the HTML.

## What's here

| Path | What it is |
|---|---|
| `index.html` | The entire dashboard: inline CSS, no JS framework, no external data source. Sections include Do Now, Sprint Score, Blocked decisions, Project Registry, Fleet (network machine status), Risks, Open Threads, Port Map, Agent Inventory, System Structure, and a Session Archive log. |
| `favicon.svg` | Site favicon. |
| `LICENSE` | All-rights-reserved notice. |

The dashboard tracks the state of several other personal projects at a point in time (PromptLab, Garden OS, Phillies Wire, DaveLLM, ShieldBox, Trailkeeper, DeckForge, Act Two Catering, Metagrid, CurlPlan, NeSy, ReadOut, Daily Prophet) along with a small home network fleet (Walter, Duncan, Home Assist, two Katanas) and a roster of personal automation agents (Jerri, Daily Prophet, Codex, Claude Code, etc.). None of that data is live — it reflects manual edits made on the dates in the commit history.

## How to run it

No build tools or dependencies. Just open the file:

```
open index.html
```

or serve it locally:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.
