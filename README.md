# James O'Connor

Building AI-native developer tools and composable application platforms.

[![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=fff)](https://www.typescriptlang.org)
[![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000)](https://react.dev)
[![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=fff)](https://www.python.org)
[![LangGraph](https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square)](https://langchain-ai.github.io/langgraph/)
[![Anthropic](https://img.shields.io/badge/Anthropic_SDK-191919?style=flat-square)](https://docs.anthropic.com)

[jim.software](https://jim.software) · [hi@jim.software](mailto:hi@jim.software)

---

## Frame

Frame is an AI-native application compositor. One shell, one assistant, one API key — routing natural-language intent across nine domain-specific apps. The shell is a [Vite Module Federation](https://github.com/nicolo-ribaudo/vite-plugin-federation) host: each sub-app loads as a true React remote with shared Redux and Carbon Design System singletons. No iframes, no page reloads. A central LLM gateway ([frame-agent](https://github.com/ojfbot/shell)) classifies intent and delegates to domain agents, so every app in the ecosystem gets AI capabilities through a single Anthropic API key.

The architectural bets: Module Federation over iframes. Domain agents over monolithic prompts. A single shared component library over per-app duplication. Kubernetes manifests ready, Vercel serving the edge layer.

## Core Workflow Framework

The internal developer platform for this ecosystem. [Core](https://github.com/ojfbot/core) is a portable Claude Code workflow framework: 30+ slash commands covering the full development lifecycle — planning, scaffolding, validating, deploying, investigating, hardening, sweeping. Each command is a self-contained skill directory with its own orchestration prompt, knowledge files, and scripts. A TypeScript CLI and VS Code extension back the same commands for CI and editor use.

One `install-agents.sh` call symlinks the full toolkit into any sibling repo. 34 Architecture Decision Records document every significant decision with context, alternatives, and rationale. A self-improvement loop (`/techdebt`) proposes patches to the framework itself — never production code.

## Daily Dev Log

Every day, a GitHub Action sweeps commits across 13 repos, Claude writes an article with structured sections, and a draft PR opens for editorial review. Merging deploys to Vercel.

Read the log at **[log.jim.software](https://log.jim.software)**

---

## Repos

| Repo | What's interesting |
|------|-------------------|
| [shell](https://github.com/ojfbot/shell) | Module Federation host + single-API-key LLM gateway for 9 domain apps |
| [core](https://github.com/ojfbot/core) | 30+ Claude Code slash commands, TypeScript workflow engine, 34 ADRs |
| [daily-logger](https://github.com/ojfbot/daily-logger) | Cron sweeps 13 repos, Claude writes an article, PR opens for editorial review |
| [cv-builder](https://github.com/ojfbot/cv-builder) | LangGraph multi-agent resume builder with visual regression CI pipeline |
| [MrPlug](https://github.com/ojfbot/MrPlug) | Chrome extension: select any DOM element, describe what's wrong, get a GitHub issue or Claude Code fix |
| [GroupThink](https://github.com/ojfbot/GroupThink) | Chrome extension: LLM-powered tab grouping — analyzes open tabs and organizes them into semantic groups |
| [purefoy](https://github.com/ojfbot/purefoy) | Team Deakins cinematography knowledge base — 348 podcast transcripts + 3,075 forum posts, Python RAG pipeline with SQLite FTS5 |
| [blogengine](https://github.com/ojfbot/BlogEngine) | AI content platform with podcast responder pipeline and Notion integration |
| [TripPlanner](https://github.com/ojfbot/TripPlanner) | AI trip planning — 11-phase SSE pipeline, 6 itinerary lens views, LangGraph agents |
| [frame-ui-components](https://github.com/ojfbot/frame-ui-components) | Shared component library consumed by 9 apps (Carbon Design System) |
| [landing](https://github.com/ojfbot/landing) | [jim.software](https://jim.software) — Vite + React + Three.js corridor canvas |
