# Matt Nanney · 186 Studios

**I build production AI for lending and other regulated industries, and I build it myself.** Seventeen years in SBA lending and banking operations, now full-time founder of [186 Studios](https://186studios.com). Every system below was architected, built, and deployed hands-on.

Johns Creek, GA (Atlanta) · Remote · [LinkedIn](https://www.linkedin.com/in/matt-nanney-8a5b0311) · [186studios.com](https://186studios.com)

---

## What I build

| Area | What that means in practice |
|---|---|
| **Document intelligence** | Vision-language models read loan files, tax returns, and policy manuals directly (no OCR pipeline) and return structured, workflow-ready data |
| **Expert systems** | Confidence-gated assistants that interview before they advise, cite their sources, and leave an audit trail |
| **Agents and MCP** | Production Model Context Protocol servers and agent workflows with explicit, reviewable permissions |
| **Private and on-prem AI** | Local LLMs (LM Studio, Ollama), quantized open-weight models, LoRA fine-tunes trained locally, hardware sizing |
| **Platforms** | Multi-model AI apps on the Cloudflare edge with credit metering and cost guardrails |

## Selected systems

Most of this work is private or client-owned, so the code is not public. Happy to walk through any of it live.

- **186 Studios Terminal.** Multi-model subscriber platform: chat, image, and video generation across Anthropic, OpenAI, and Google in one interface. Astro, React, Cloudflare Workers, Pages, and D1. Hard parts: per-request credit metering, cost guardrails, and tenant gating.
- **SBA Oracle and UW Oracle.** Confidence-gated expert systems for SBA 7(a)/504 lending and commercial insurance underwriting. They read the file, cite the source, and answer like a veteran underwriter. Hard part: making an LLM behave like a regulated advisor.
- **Apollo Deep Solve and Consensus.** Two reasoning engines. Apollo breaks a tangled problem into parts, solves each, and challenges the chain adversarially before answering. Consensus has 2 to 6 models critique and revise each other's answers over several rounds, then merges them, with every draft kept visible.
- **Read-only SQL MCP server.** Gives a model SELECT-only SQL over a DuckDB and Parquet data lake of 28B+ rows. Hardened against escape: no file paths, row caps, watchdog timeouts.
- **Calypso.** Trading research platform: multi-strategy execution engine with layered risk controls, a Strategy Lab for backtesting, an API-connected execution layer, and a tick-data archive. Research preview.

## Stack

`Python` `TypeScript` `React` `Astro` `Node.js` `FastAPI` `Electron` `Cloudflare Workers / Pages / D1` `DuckDB` `Parquet` `Docker` `Anthropic Claude API` `OpenAI API` `MCP` `LM Studio` `Ollama` `LoRA`

## Background

Seventeen years in SBA lending operations, including eight consecutive years with $0 in SBA compliance penalties. Self-taught engineer: desk-built automations grew into a cross-departmental automation task force, then a division-level AI and process automation role, then 186 Studios. I build for compliance review because I spent years on the other side of it.

## Working together

Fractional AI leadership, scoped builds, architecture reviews, and expert calls on SBA lending and AI adoption in banking. Reach me through [186studios.com/contact](https://186studios.com/contact) or LinkedIn.
