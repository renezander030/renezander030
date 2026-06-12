![banner](banner.png)

# Hey, I'm René

I build **automation CLIs and AI-agent tooling** — sharp single-purpose command-line tools, plus the production patterns (approval gates, schema validation, audit logs) that let agents touch real systems safely.

If you script things, run agents, or want CLIs that do one job well with JSON output you can pipe — this profile is for you. **Follow for new CLIs and production-AI patterns** as they ship.

[![Follow](https://img.shields.io/github/followers/renezander030?label=Follow&style=social)](https://github.com/renezander030?tab=followers) [![capcut-cli stars](https://img.shields.io/github/stars/renezander030/capcut-cli?label=capcut-cli&style=social)](https://github.com/renezander030/capcut-cli) [![Profile views](https://komarev.com/ghpvc/?username=renezander030&label=Profile+views&color=14b8a6&style=flat)](https://github.com/renezander030)

## Start here

- **[capcut-cli](https://github.com/renezander030/capcut-cli)** — CLI to edit CapCut / JianYing drafts (subtitles, timing, speed, templates, cut long-form → shorts). No API; reads `draft_content.json` directly
- **[draftcat](https://github.com/renezander030/draftcat)** — governed AI pipelines for service businesses: deterministic-first, operator-approved, single Go binary (MIT)
- **[agentic-task-system](https://github.com/renezander030/agentic-task-system)** — your task manager is the best agent memory you're not using: hybrid retrieval (RRF) over TickTick / Obsidian
- **[agent-approval-gate](https://github.com/renezander030/agent-approval-gate)** — `draft → validate → approve → dispatch → audit` pattern with JSON schemas, n8n workflow, and email-approval example
- **[browserground](https://github.com/renezander030/browserground)** — local UI-grounding specialist for hybrid AI agents: Qwen3-VL-2B LoRA, screenshot + target → strict JSON bbox. Drop-in for Claude Code, Codex, browser-use

## The series

**Production AI Automation Notes** — a running set of repos and gists on:
- approval gates for AI agents
- MCP server security (permissions, tenants, audit logs)
- Claude Code policies for company repos
- n8n workflows with human approval
- audit-log schemas

Follow if you're building agents that need to work outside demos.

## Recent gists

| Gist | Topic |
|---|---|
| [LLM cost tracking in Go: a per-model price model on top of token budgets (PAAN #9)](https://gist.github.com/renezander030/2de8a7c169d0eac0d857f52d2cda061e) | cost_per_1k_input / cost_per_1k_output / dollar spend / BUDGET_BLOCKED / OpenRouter / Go (June 2026) |
| [Stateless JSONL queue runner: a CLI into n8n / Make / Coze, no HTTP server (PAAN #8)](https://gist.github.com/renezander030/807559488f523892fc25870bf9501d29) | n8n Execute Command / stateless / JSONL / no daemon / capcut-cli serve (May 2026) |
| [CapCut / JianYing draft_content.json schema cheat sheet](https://gist.github.com/renezander030/80823f1d47081c312d2c1f9edd20dc22) | every top-level key + version differences + jq one-liners (May 2026) |
| [JianYing 6.0+ draft_content.json encryption: detection and workarounds](https://gist.github.com/renezander030/521e6c6e8590a2a6e917009d9313bc55) | 剪映 6.0 / 7.x / 10.3 / CapCut International — verbatim error strings (May 2026) |
| [Driving CapCut / JianYing video drafts from an LLM agent (PAAN #4)](https://gist.github.com/renezander030/866bd85789c5902471f8f5fc86d09342) | capcut-cli / bubble-text / audio-fade / mix-mode / Claude / DeepSeek / GLM (May 2026) |
[All gists →](https://gist.github.com/renezander030)

## Open source contributions

| Project | PR | What |
|---|---|---|
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | [#835](https://github.com/Tencent/WeKnora/pull/835) ![Merged](https://img.shields.io/badge/Merged-purple) | Parallel tool calling support |
| [steveyegge/beads](https://github.com/steveyegge/beads) | [#2884](https://github.com/gastownhall/beads/pull/2884) ![Merged](https://img.shields.io/badge/Merged-purple) | Multi-project support, Notion sync, backup/restore |
| [e2b-dev/infra](https://github.com/e2b-dev/infra) | [#2273](https://github.com/e2b-dev/infra/pull/2273) ![Merged](https://img.shields.io/badge/Merged-purple) | Local dev docs: prerequisites, verification steps, troubleshooting |
| [pacifio/cersei](https://github.com/pacifio/cersei) | [#10](https://github.com/pacifio/cersei/pull/10) ![Merged](https://img.shields.io/badge/Merged-purple) | Native Google Gemini provider + Cohere & SambaNova support |

[All merged PRs](https://github.com/pulls?q=is%3Apr+author%3Arenezander030+is%3Amerged+archived%3Afalse)

[![GitHub stats](https://github-readme-stats.vercel.app/api?username=renezander030&show_icons=true&hide=stars,issues&hide_border=true&card_width=440)](https://github.com/renezander030)

---

**Stack:** Python, Go, TypeScript, Node.js, Kubernetes, Linux, systemd, vector databases, LLM APIs.

**Website:** [renezander.com](https://renezander.com)

## Production AI Automation Notes

A gist series on production-grade patterns for AI pipelines. Each entry covers one pattern with copy-pasteable code.

| # | Topic | Pattern |
|---|---|---|
| [#1](https://gist.github.com/renezander030/9069db775e494ffd2cdd5a09adf83add) | Agent Approval Gates | Schema-validated proposals, human review, deterministic dispatch |
| [#2](https://gist.github.com/renezander030/a7d99ad94b97f7943a9a04016d62faaa) | Token Budgets | Per-step, per-pipeline, per-day enforcement |
| [#3](https://gist.github.com/renezander030/c7bd6d5c4088e24d3add043720284453) | Agentic Knowledge Base | Karpathy-style LLM wiki with pluggable adapters |
| [#4](https://gist.github.com/renezander030/866bd85789c5902471f8f5fc86d09342) | CapCut / JianYing from an LLM agent | Deterministic JSON command boundary |
| [#5](https://gist.github.com/renezander030/8a23e32cde0c882a5aa069c4bfdf697f) | SQLite Dedup + Crash Safety | WAL mode, seen_items, audit log |
| [#6](https://gist.github.com/renezander030/213ffdf1ab1bdb169881927bc7080270) | Prompt-Injection Defense | Input sanitization, schema validation |
| [#7](https://gist.github.com/renezander030/7780cbc0b3ad4e802e8fba8bfc1c3a66) | PDF Cite Verification | Auditable LLM extraction with per-fragment bounding boxes |
| [#8](https://gist.github.com/renezander030/807559488f523892fc25870bf9501d29) | Stateless JSONL Queue Runner | Wire a CLI into n8n / Make / Coze, no HTTP server |
| [#9](https://gist.github.com/renezander030/2de8a7c169d0eac0d857f52d2cda061e) | LLM Cost Tracking | Per-model price model + dollar spend on top of token budgets |

Reference implementation for entries #1, #2, #5, #6, #7, #9: [draftcat](https://github.com/renezander030/draftcat) (Go, MIT).

[All gists →](https://gist.github.com/renezander030)
