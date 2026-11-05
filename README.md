# Hi, I'm trleo

**AI Solution Lead — building production-ready AI tooling and contributing real fixes to open source.**

I work on the practical side of AI in production: evaluation, guardrails, observability, governance, and reliability — and on the open-source projects that other engineers rely on. My contributions are small, verifiable, and reviewed, not cosmetic.

## What I build

### LLM Production Readiness Audit
A deterministic, offline CLI that audits LLM projects for production readiness across five areas — evaluation, guardrails, observability, governance, and reliability. 15 checks, scored GO / CONDITIONAL GO / NO-GO reports, with a passing and a failing sample included.

- https://github.com/trleo/llm-production-readiness-audit

### Skill Cleaner
A CLI that audits, deduplicates, and prunes AI agent skills across Claude, Cursor, and Antigravity. Duplicate detection by name, content hash, and similarity — with approval-file-only pruning, quarantine with a manifest, and restore. It never deletes.

- https://github.com/trleo/skill-cleaner

## Merged contributions to other projects

- **chunkhound — SSRF protection in websearch** ([#475](https://github.com/chunkhound/chunkhound/pull/475)): added a shared SSRF validator so search-result URLs are checked before fetching, including hop-by-hop redirect validation, secure-by-default settings, and behavioural tests. Approved after three review rounds and merged into main.
- **scalar — Auth badge overflow** ([#10841](https://github.com/scalar/scalar/pull/10841)): fixed a floating panel that briefly overflowed the viewport while hovering an "Auth Required" badge, with a regression test. Merged the same day it was opened.
- **Ovenbird — `cos power` command** ([#133](https://github.com/NobiResearch/Ovenbird/pull/133)): a new read-only command reporting macOS power assertions. Ovenbird's first outside contribution; thanked in the 0.8.0 release notes.
- **Ovenbird — Vitals trend sparklines** ([#157](https://github.com/NobiResearch/Ovenbird/pull/157)): 30-day trend sparklines for Vitals, with a collecting state while data accumulates.

## Also in review

Open pull requests under review with maintainers, including fixes for good_job (NULL queue/job-class charts), rclone (archive backend move-onto-itself), tenacity (LoggerProtocol compatibility with loguru), vite (CSS HMR query handling), glow (style-path expansion), vLLM (MFU/MBU for renamed quantisation methods), TheAlgorithms/Python, and skills-janitor.

## Focus areas

- LLM evaluation, guardrails, and production readiness
- AI agent tooling and skill management
- Open-source security and reliability fixes
- Python, with working contributions across Go, TypeScript, and Ruby projects

## Principles

- Real work over activity: merged fixes, not empty commits.
- Verified end to end: reproduction first, tests green, honest about limits.
- Small, reviewable changes that maintainers can actually merge.
