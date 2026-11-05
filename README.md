# Hi, I'm trleo

I work where AI systems meet real codebases — taking something that works in a demo and making it hold up in production, inside the systems people already run.

That usually means working inside other people's projects, not just my own: reading the existing code, reproducing the problem, writing a small fix that fits the project's conventions, and iterating through review until a maintainer is comfortable shipping it.

## What I build

### LLM Production Readiness Audit
A deterministic, offline CLI that audits LLM projects for production readiness across five areas — evaluation, guardrails, observability, governance, and reliability. 15 checks, scored GO / CONDITIONAL GO / NO-GO reports, with a passing and a failing sample included.

- https://github.com/trleo/llm-production-readiness-audit

### Skill Cleaner
A CLI that audits, deduplicates, and prunes AI agent skills across Claude, Cursor, and Antigravity. Duplicate detection by name, content hash, and similarity — with approval-file-only pruning, quarantine with a manifest, and restore. It never deletes.

- https://github.com/trleo/skill-cleaner

## Shipped into other people's projects

- **chunkhound — SSRF protection in websearch** ([#475](https://github.com/chunkhound/chunkhound/pull/475)): added a shared SSRF validator so search-result URLs are checked before fetching, including hop-by-hop redirect validation, secure-by-default settings, and behavioural tests. Approved after three review rounds and merged into main.
- **scalar — Auth badge overflow** ([#10841](https://github.com/scalar/scalar/pull/10841)): fixed a floating panel that briefly overflowed the viewport while hovering an "Auth Required" badge, with a regression test. Merged the same day it was opened.
- **Ovenbird — `cos power` command** ([#133](https://github.com/NobiResearch/Ovenbird/pull/133)): a new read-only command reporting macOS power assertions. Ovenbird's first outside contribution; thanked in the 0.8.0 release notes.
- **Ovenbird — Vitals trend sparklines** ([#157](https://github.com/NobiResearch/Ovenbird/pull/157)): 30-day trend sparklines for Vitals, with a collecting state while data accumulates.

## Also in review

Open pull requests under review with maintainers, including fixes for good_job (NULL queue/job-class charts), rclone (archive backend move-onto-itself), tenacity (LoggerProtocol compatibility with loguru), vite (CSS HMR query handling), glow (style-path expansion), vLLM (MFU/MBU for renamed quantisation methods), TheAlgorithms/Python, and skills-janitor.

## How I work

- Reproduce first, then fix — in the project's own test setup, not in isolation.
- Small, reviewable changes that fit the codebase's existing patterns.
- Verified end to end: tests green, honest about what could not be reproduced locally.
- Security and reliability fixes first — the kind of work that has to be right before it ships.
- Python first, with working contributions across Go, TypeScript, and Ruby projects.

---

## Contact

- WhatsApp: [+8801737923848](https://wa.me/8801737923848)
- LinkedIn: [linkedin.com/in/trleoo](https://www.linkedin.com/in/trleoo/)
