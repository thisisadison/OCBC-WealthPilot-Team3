OCBC WealthPilot — Prototype Overview

Summary:
This is a front-end prototype (static HTML/CSS/JS) for "WealthPilot" — an AI-assisted financial planning demo. It lets users build an AI team of goal-focused agents (Property Planner, Retirement Planner, Growth Strategist, Income Builder) plus an Orchestrator that balances their recommendations into a single plan. The prototype includes flows for selecting agents, entering goal-specific details, assessing risk, linking accounts, and generating a recommended allocation.

Key Files:
- deepseek_nonsense.html: Primary interactive prototype with agent definitions, UI screens, and logic.
- wealth_prototype.html: Alternate entry point (if present) — verify before publishing.

How it works:
- Users pick up to 2 agents (configurable in the file) and optionally link accounts.
- Agents present insights; the Orchestrator synthesizes a recommendation and sample allocation across four asset classes.
- UI is mobile-optimized (phone frame) but served as static HTML.

Run locally:
1. cd to this folder
2. python3 -m http.server 8000
3. Open http://<MACHINE_IP>:8000/deepseek_nonsense.html on a phone/browser (same Wi‑Fi)

Publishing:
- Commit & push to your GitHub repo and enable GitHub Pages; copy wealth_prototype.html to index.html for root URL.

Notes & TODOs:
- Agent themes and selection limits are configurable in the AGENTS array inside deepseek_nonsense.html.
- Some other HTML files in the project may contain stale 6-agent definitions; consider synchronizing them if you host the whole site.

Contact:
For changes to UI interactions or publishing help, ask and provide which behavior or screens to modify.