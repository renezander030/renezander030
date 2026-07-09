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
| [Cross-source agent memory for Claude Code: GitHub + Notion + your task app, one RRF query](https://gist.github.com/renezander030/10272100535f9ab1ea0eae193cf3936f) | cross-source retrieval / fuse GitHub Notion TickTick / one ranked list / composite adapter / RRF / no vector database / MCP / Claude Code (June 2026) |
| [GitHub issues as agent memory for Claude Code — hybrid retrieval, no vector DB](https://gist.github.com/renezander030/1fa5f038e8e1161a75300a34ab534bb2) | github mcp / github issues as agent memory / issues + discussions / fine-grained PAT / hybrid RRF retrieval / no vector database / Claude Code (June 2026) |
| [Notion as agent memory for Claude Code — hybrid retrieval over your pages](https://gist.github.com/renezander030/33571e8d9e8ea5502e4b6848b2557f05) | notion mcp server / claude code notion / notion agent memory / share database with integration / hybrid RRF / no vector database (June 2026) |
| [AI agent action audit trail in SQLite: who approved what, when, GDPR Art. 22 (PAAN #15)](https://gist.github.com/renezander030/ad81c7a805a09a844983f881e2c487e5) | AI agent audit trail / who approved what when / GDPR Article 22 / automated decision provenance / append-only approval log / SQLite / Go (June 2026) |
| [Self-improving voice AI agent: human-approved prompt diffs, Dograh learning loop (PAAN #14)](https://gist.github.com/renezander030/262d8b8c44b4cddf51b3b84c40f3f669) | self-improving voice agent / human-in-the-loop prompt update / Learning-Item review / Dograh webhook / workflow auto-versioning / DACH voice screening / Go (June 2026) |

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

**Website:** [renezander.com](https://renezander.com) · **YouTube:** [@zanderforge](https://www.youtube.com/@zanderforge)

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
| [#10](https://gist.github.com/renezander030/2f0754a4babd185d22d8498d5dc04982) | Deterministic Step Pipelines | Fixed typed steps; the LLM never picks the next action |
| [#11](https://gist.github.com/renezander030/a058fc0d5e7e7fa209d30cfa48e82ebb) | Pipeline Fixture Testing | Dry-run pipelines from JSON fixtures; zero API calls, deterministic CI |
| [#12](https://gist.github.com/renezander030/a28f118dec07d275ccc825aa833aba92) | LLM Skills as YAML | Prompt + output_schema + role in versioned YAML; validated by a linter |
| [#13](https://gist.github.com/renezander030/26d46d4c7fb9ab1b43fe19bc5bad6d07) | Inbound Agent Webhook Auth | Constant-time bearer token, fail-closed on empty secret, async 202 dispatch |
| [#14](https://gist.github.com/renezander030/262d8b8c44b4cddf51b3b84c40f3f669) | Self-Improving Voice Agent | Human-approved prompt diffs; harvest > group > propose > 2 approval gates > git commit > staging smoke > auto-versioned publish |
| [#15](https://gist.github.com/renezander030/ad81c7a805a09a844983f881e2c487e5) | AI Action Audit Trail | Append-only `action_approvals` table: who approved which payload, when; gate-violation query; GDPR Art. 22 provenance |

Reference implementation for entries #1, #2, #5, #6, #7, #9, #10, #11, #12, #13: [draftcat](https://github.com/renezander030/draftcat) (Go, MIT).

[All gists →](https://gist.github.com/renezander030)
