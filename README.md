# James O'Connor

Building AI-powered developer tools — multi-agent systems, MCP servers, Claude Code skills, and the tooling infrastructure that makes AI coding assistants better.

[![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=fff)](https://www.typescriptlang.org)
[![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000)](https://react.dev)
[![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=fff)](https://www.python.org)
[![Claude API](https://img.shields.io/badge/Claude_API-191919?style=flat-square)](https://docs.anthropic.com)
[![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-4B32C3?style=flat-square)](https://modelcontextprotocol.io)

[jim.software](https://jim.software) · [log.jim.software](https://log.jim.software) · [hi@jim.software](mailto:hi@jim.software)

---

## What I Build

**AI developer tools** — the infrastructure layer between LLMs and software engineering workflows. Currently shipping:

- **35+ Claude Code skills** — portable prompt-driven workflows covering the full dev lifecycle ([core](https://github.com/ojfbot/core))
- **Custom ESLint plugin** — 8 rules enforcing monorepo safety, including source map leak prevention ([cv-builder](https://github.com/ojfbot/cv-builder))
- **Claude Code hooks** — PreToolUse hooks inject ESLint violations as LLM context before edits; PostToolUse hooks detect regressions
- **Skill telemetry pipeline** — JSONL-based tracking of skill/tool usage across sessions, surfaced as PR comments and daily blog telemetry

## Frame OS

An AI-native application compositor. One shell, one assistant, one API key — routing natural-language intent across domain-specific apps via [Vite Module Federation](https://github.com/nicolo-ribaudo/vite-plugin-federation) with shared React/Redux singletons and Carbon Design System.

## Daily Dev Log

Every day, a GitHub Action sweeps commits across 13 repos, Claude writes a structured article, 4 editorial personas review it, and the final draft deploys to **[log.jim.software](https://log.jim.software)**.

---

## Repos

| Repo | Description |
|------|-------------|
| [core](https://github.com/ojfbot/core) | Claude Code workflow framework — 35+ skills, TypeScript engine, 40 ADRs, hooks-based telemetry |
| [cv-builder](https://github.com/ojfbot/cv-builder) | AI resume builder — 7-agent LangGraph pipeline, custom ESLint plugin (8 rules), visual regression CI |
| [daily-logger](https://github.com/ojfbot/daily-logger) | Automated dev blog — Claude API draft + 4-persona editorial council + GitHub Pages deploy |
| [shell](https://github.com/ojfbot/shell) | Frame OS host — Module Federation, frame-agent LLM gateway, K8s manifests |
| [MrPlug](https://github.com/ojfbot/MrPlug) | Chrome extension — AI UI/UX feedback, DOM inspection, GitHub issue generation |
| [GroupThink](https://github.com/ojfbot/GroupThink) | Chrome extension — LLM-powered semantic tab grouping |
| [purefoy](https://github.com/ojfbot/purefoy) | Roger Deakins knowledge base — 348 transcripts + 3,075 forum posts, Python RAG pipeline |
| [BlogEngine](https://github.com/ojfbot/BlogEngine) | AI blog platform — podcast responder pipeline, Notion integration |
| [TripPlanner](https://github.com/ojfbot/TripPlanner) | AI trip planning — 11-phase SSE pipeline, 6 itinerary lens views |
| [frame-ui-components](https://github.com/ojfbot/frame-ui-components) | Shared React component library (Carbon Design System) for Frame OS apps |
| [hailstone](https://github.com/ojfbot/hailstone) | Chuuk Lagoon dive site map — Mapbox GL JS, Firebase |
| [landing](https://github.com/ojfbot/landing) | [jim.software](https://jim.software) — portfolio site |
