[![René Zander — AI agents that act on today's facts; sourced answers and human-approved actions in DACH](banner-sep27.png)](https://renezander.com/knowledge-graph-consulting/)

# René Zander

**Enterprise AI architect · Context layers for AI agents · DACH**

I help teams whose AI assistants already read chat, tickets, wiki and CRM answer from **current, cited facts** and take **actions a person approves**. I build the context layer on your own tenant, with delegated access, a temporal knowledge graph and an audit trail. We can start with one governed workflow; implementation is billed by the hour with an estimate for each phase.

**Explore the work:** [50-second demo and case study](https://renezander.com/case-studies/operational-context-layer-governed-actions/) · [Consulting approach](https://renezander.com/knowledge-graph-consulting/) · [Discuss your workflow](https://renezander.com/#meeting)

**Building this yourself?** Follow this profile for implementation notes and open-source tools for governed AI systems.

The case study describes a production workflow. Its public demo and screenshots use fictional records to protect the client.

## Start with the problem you have

| If you need to… | See how I approach it |
| --- | --- |
| Find the current customer decision across disconnected systems | [Operational context layer](https://renezander.com/case-studies/operational-context-layer-governed-actions/) — sources, timestamps and permissions travel with each answer |
| Let an agent act without giving it unchecked write access | [draftcat](https://github.com/renezander030/draftcat) and [agent-approval-gate](https://github.com/renezander030/agent-approval-gate) — proposals, human verdicts and audited dispatch |
| Keep track of what was true when | [graphiti-local](https://github.com/renezander030/graphiti-local) — a local temporal knowledge graph with read-only MCP retrieval and human-gated fact ingestion |

## Open source and engineering proof

- [agentic-task-system](https://github.com/renezander030/agentic-task-system) connects existing task and knowledge tools to agent context, with provenance, reviewed writes and undo. The underlying systems remain the source of truth.
- [skillgate](https://github.com/renezander030/skillgate) runs deterministic completion checks for AI coding agents before commit or publication.
- My merged contributions include [RAG query validation before logging in Tether's QVAC](https://github.com/tetherto/qvac/pull/3729) and [GPT-5/o-series vision support in WeKnora](https://github.com/Tencent/WeKnora/pull/2614). [See all merged PRs](https://github.com/pulls?q=is%3Apr+author%3Arenezander030+is%3Amerged+archived%3Afalse).

I also build creator tooling: [capcut-cli](https://github.com/renezander030/capcut-cli) is an independent CLI for editing CapCut/JianYing project files.

## Production AI Automation Notes

I publish implementation notes for people building agents beyond demos. Recent examples:

- [Permission-aware retrieval without count, title or provenance leaks](https://gist.github.com/renezander030/4c97bc473db055f2aa6d71be4c4551ce)
- [Why an agent proposes facts but never writes directly to the knowledge graph](https://gist.github.com/renezander030/a3600b3378b01f00080f9f41150f16d2)
- [Validate a RAG query before its first log line](https://gist.github.com/renezander030/34d7197e2d9f83d986766742ab979d04)

[Browse all notes](https://gist.github.com/renezander030)

## Work with me

I work with DACH teams that need AI to answer from their actual operational state and act within clear permissions. A first engagement can review one workflow's sources, identity, write path and failure modes before a phased build.

[Discuss your workflow](https://renezander.com/#meeting) · [Email me](mailto:rene@renezander.com) · [Malt profile and references](https://www.malt.de/profile/renezander)
