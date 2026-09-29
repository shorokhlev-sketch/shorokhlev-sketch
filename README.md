# Lev Skorokhodov

AI engineer. I build LLM agents and the harness around Claude and Codex, and take them from prototype to production.

- Agents and harness. Parallel Claude and Codex subagents, instruction files per task type, acceptance by diff, tests and render checks.
- Prototype to production. VPS, nginx, systemd, CI, snapshots before every deploy. 7 services live on one server.
- Web and visual. Interfaces, design systems, AI images and video.

## Projects

| Project | Result | Links |
|---|---|---|
| Floor plan pipeline | Turns a 114 page architectural PDF into vector plans for 279 apartments on 25 floors. 5 Sonnet agents close 25 floors in about 2 minutes. | [code](https://github.com/shorokhlev-sketch/floorplan-pipeline), [live](https://lab.prfo.design/maisi/select.html) |
| Trade System | Accounting system and invoice OCR bot for a produce importer. The bot handled 10 to 30 handwritten invoices a day. The client bought out the code; I walk through the architecture on request. | [demo](https://lab.prfo.design/trade/) |
| Telegram store | Shop for used Apple devices inside Telegram: one bot wizard lists a lot in the channel, the Mini App and the website. 340 tests run in 11 seconds. | [code](https://github.com/shorokhlev-sketch/telegram-store) |
| Content Factory | Cuts a 23 minute episode into 5 to 7 vertical clips with burned subtitles for about $0.27 in API cost. | [code](https://github.com/shorokhlev-sketch/clip-factory), [live](https://factory.prfo.design) |
| 26 MAISI | Sales site and CRM for a 26 floor tower in Batumi: 279 units, every lead tracked to its source. | [site code](https://github.com/shorokhlev-sketch/apartment-picker), [CRM code](https://github.com/shorokhlev-sketch/realestate-crm), [live](https://lab.prfo.design/maisi/) |
| AI video production | Fashion and product films on Higgsfield: 6 campaigns, 244 generated frames, 47 clips. Claude works from a storyboard with a job bus. | [code](https://github.com/shorokhlev-sketch/ai-video-pipeline), [visuals](https://prfo.design/visual/) |
| matscout | Personal course project: MCP server with 25 tools and a two phase research agent over materials databases. | [code](https://github.com/shorokhlev-sketch/matscout), [live](https://matscout.prfo.design) |

Harness: [claude-skills](https://github.com/shorokhlev-sketch/claude-skills), Claude Code skills, working rules, agent loop template and multi-agent workflow examples.

## Stack

Claude Code, Codex, Claude and OpenAI APIs, MCP, Python, TypeScript, React, Node.js, FastAPI, Fastify, aiogram, Telegram Mini Apps, PostgreSQL, SQLite, Playwright, Figma, Higgsfield, nginx, systemd, Docker.

## Contacts

- Portfolio: https://lab.prfo.design/portfolio/
- Telegram: [@prfowax](https://t.me/prfowax)
