![banner](banner.png)

# Hey, I'm René

I publish practical gates for AI-generated work: approval gates, schema validation, audit logs, MCP server patterns, and deterministic code-review checks.

If you're building agents that need to touch real systems safely — not demo agents — this profile is for you.

## Start here

- **[agent-approval-gate](https://github.com/renezander030/agent-approval-gate)** — `draft → validate → approve → dispatch → audit` pattern with JSON schemas, n8n workflow, and email-approval example
- **[agentproof-react](https://github.com/renezander030/agentproof-react)** — npm CLI that blocks common AI-generated React/Next.js shipping failures before release
- **mcp-internal-tools-starter** — TypeScript MCP starter with permissions, tenants, audit logs, approval tools *(coming next week)*
- **[leanix-mcp-integration](https://github.com/renezander030/leanix-mcp-integration)** — enterprise GraphQL MCP integration (LeanIX EAM)
- **[fixclaw](https://github.com/renezander030/fixclaw)** — Claude Code runtime discipline for deterministic AI pipelines (Go)

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
| [CapCut / JianYing draft_content.json schema cheat sheet](https://gist.github.com/renezander030/80823f1d47081c312d2c1f9edd20dc22) | every top-level key + version differences + jq one-liners (May 2026) |
| [JianYing 6.0+ draft_content.json encryption: detection and workarounds](https://gist.github.com/renezander030/521e6c6e8590a2a6e917009d9313bc55) | 剪映 6.0 / 7.x / 10.3 / CapCut International — verbatim error strings (May 2026) |
| [Driving CapCut / JianYing video drafts from an LLM agent (PAAN #4)](https://gist.github.com/renezander030/866bd85789c5902471f8f5fc86d09342) | capcut-cli / bubble-text / audio-fade / mix-mode / Claude / DeepSeek / GLM (May 2026) |
| [Hybrid AI agents: a 2B local VLM beats GPT-4V at browser-use UI grounding](https://gist.github.com/renezander030/947baf076f95c50db5a3e3d4b16cbd14) | browserground / Qwen3-VL / ScreenSpot-v2 / browser-use / Skyvern / Claude Computer Use (May 2026) |
| [Claude Code with local LLMs: ANTHROPIC_BASE_URL, Ollama, LM Studio, vLLM, LiteLLM](https://gist.github.com/renezander030/39249215616a095d74fe6c66b0348641) | gpt-oss / qwen3-coder / glm-4.7 setup + tool-call failures (Apr 2026) |

[All gists →](https://gist.github.com/renezander030)

## Open source contributions

| Project | PR | What |
|---|---|---|
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | [#835](https://github.com/Tencent/WeKnora/pull/835) ![Merged](https://img.shields.io/badge/Merged-purple) | Parallel tool calling support |
| [steveyegge/beads](https://github.com/steveyegge/beads) | [#2884](https://github.com/gastownhall/beads/pull/2884) ![Merged](https://img.shields.io/badge/Merged-purple) | Multi-project support, Notion sync, backup/restore |
| [e2b-dev/infra](https://github.com/e2b-dev/infra) | [#2273](https://github.com/e2b-dev/infra/pull/2273) ![Merged](https://img.shields.io/badge/Merged-purple) | Local dev docs: prerequisites, verification steps, troubleshooting |
| [pacifio/cersei](https://github.com/pacifio/cersei) | [#10](https://github.com/pacifio/cersei/pull/10) ![Merged](https://img.shields.io/badge/Merged-purple) | Native Google Gemini provider + Cohere & SambaNova support |

[All merged PRs](https://github.com/pulls?q=is%3Apr+author%3Arenezander030+is%3Amerged+archived%3Afalse)

---

**Stack:** Go, TypeScript, Node.js, Kubernetes, Linux, systemd, vector databases, LLM APIs.

**Website:** [renezander.com](https://renezander.com)
