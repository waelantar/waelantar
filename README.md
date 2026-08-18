# Wael Antar

Software engineer building **Angular/TypeScript applications for a production voice-AI platform** ([Romulus](https://us.romulus.live/)) and contributing to **open-source AI agent infrastructure**.

Currently: shipping call-analytics and PBX features by day; working on agent frameworks, LLM inference optimization, and retrieval systems by night. Open to relocation in Western Europe (EU Blue Card eligible).

## Open source

Contributions to [HKUDS/nanobot](https://github.com/HKUDS/nanobot) (AI agent framework):

- **Merged** — token-based capping of the history digest in system prompts, replacing character-based limits for consistent context sizing across languages ([#4352](https://github.com/HKUDS/nanobot/pull/4352))
- **Merged** — normalized sender-ID types at pairing-store boundaries, fixing IDs silently treated as unapproved ([#4433](https://github.com/HKUDS/nanobot/pull/4433))
- **Reported** a concurrency race in per-run hook handling ([#4408](https://github.com/HKUDS/nanobot/issues/4408)) — fixed and merged by maintainers ([#4425](https://github.com/HKUDS/nanobot/pull/4425))
- Open: read-only conversation-history search tool ([#4439](https://github.com/HKUDS/nanobot/pull/4439))

Studying the internals of [earendil-works/pi](https://github.com/earendil-works/pi) (TypeScript agent harness) — contributions in progress.

## Selected work

- **[Polyglot Engine](https://github.com/waelantar/scraper)** — multithreaded web crawler in pure-stdlib Python (hand-built thread pool, bounded MPMC queue, robots.txt + rate limiting) feeding a TypeScript CLI through a shared SQLite contract
- **[ATTS](https://github.com/waelantar/ATTS_Complete_Free_Package)** — Adaptive Test-Time Scaling: difficulty-adaptive LLM inference compute, ~28% token savings at ~2% accuracy cost
- **nanolm-derja** — pretraining experiments for a small Tunisian-Arabic language model (nanoGPT-style)

## Background

2 years production Angular (17→20 migration, reactive stores, shared component library) · fullstack internships (Spring Boot, Django/Next.js) · AWS Solutions Architect Associate & AI Practitioner · FR/EN C1

📫 [antarwael@ieee.org](mailto:antarwael@ieee.org) · [LinkedIn](https://www.linkedin.com/in/wael-antar/)
