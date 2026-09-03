# Wael Antar

Software engineer working across **TypeScript product interfaces, API integrations and real-time workflows** for [Romulus](https://us.romulus.live/), a production voice-AI and cloud-PBX platform operating within Voxloud. I also build and document small, testable systems in Python and TypeScript, and contribute to **open-source AI-agent infrastructure**.

I work on call analytics, PBX workflows, integrations and shared frontend architecture. Based in Tunisia and open to employer-sponsored relocation in Western Europe.

## Open source

Contributions to [HKUDS/nanobot](https://github.com/HKUDS/nanobot) (AI agent framework):

- **Merged** — token-based capping of the history digest in system prompts, replacing character-based limits for consistent context sizing across languages ([#4352](https://github.com/HKUDS/nanobot/pull/4352))
- **Merged** — normalized sender-ID types at pairing-store boundaries, fixing IDs silently treated as unapproved ([#4433](https://github.com/HKUDS/nanobot/pull/4433))
- **Reported** a concurrency race in per-run hook handling ([#4408](https://github.com/HKUDS/nanobot/issues/4408)) — fixed and merged by maintainers ([#4425](https://github.com/HKUDS/nanobot/pull/4425))
- **Open** — read-only conversation-history search tool ([#4439](https://github.com/HKUDS/nanobot/pull/4439))
- **Open** — make ephemeral SDK runs read prior context without mutating session files or cached state ([#5471](https://github.com/HKUDS/nanobot/pull/5471))

Open contribution to [Future AGI](https://github.com/future-agi/future-agi), an AI-evaluation platform:

- **Open** — preserve existing evaluation results while safely renaming dataset evals across the UI and backend ([#2261](https://github.com/future-agi/future-agi/pull/2261)); full Docker-backed integration tests remain pending locally

## Selected work

- **[Telco Troubleshooting Agent](https://github.com/waelantar/telco-troubleshooting-agent)** — post-competition portfolio edition of an evidence-backed multi-vendor network troubleshooting workflow created for the ITU/Zindi challenge: allow-listed read-only commands, deterministic fault localization, forwarding-path tracing and claim verification in a fully synthetic Cisco/Huawei/H3C lab. Tests and CI are included. No leaderboard, production-network, client or deployed-LLM claim.
- **[Polyglot Engine](https://github.com/waelantar/polyglot-engine)** — completed terminal-first research tool: a pure-stdlib Python crawler (hand-built thread pool, bounded MPMC queue, robots.txt + rate limiting) and a TypeScript/Node terminal connected through a shared SQLite contract; checksummed, crash-recoverable JSONL session journal and an offline verification gate. [Build story](https://medium.com/@antarwael189/i-built-a-terminal-research-agent-from-a-web-crawler-heres-the-debugging-trail-i-refused-to-edit-7674343142fc)
- **[EvalGate](https://github.com/waelantar/evalgate)** — personal project, in progress: a local-first system for governed document ingestion, hybrid retrieval, evidence inspection and reproducible retrieval evaluation. No live-model, client, deployment or production-performance claim.
- **[ATTS](https://github.com/waelantar/ATTS_Complete_Free_Package)** — Adaptive Test-Time Scaling: difficulty-adaptive LLM inference compute, ~28% token savings at ~2% accuracy cost

## Background

2 years production Angular (17→20 migration, reactive stores, shared component library) · fullstack internships (Spring Boot, Django/Next.js) · AWS Solutions Architect Associate & AI Practitioner · FR/EN C1

📫 [antarwael@ieee.org](mailto:antarwael@ieee.org) · [LinkedIn](https://www.linkedin.com/in/wael-antar/)
