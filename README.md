# Open WebUI (open-webui)

Open WebUI is a self-hosted, open-source web UI for LLMs (notably Ollama and OpenAI-compatible backends). It exposes a REST API for chats, models, prompts, knowledge (RAG), users, and tools. Distributed under a modified BSD-3-Clause license; primarily run via Docker or pip on your own infrastructure.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/open-webui/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- LLM, Open Source, Self-Hosted, Ollama, Chat UI, RAG

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Open WebUI API
REST API exposed by a self-hosted Open WebUI instance. Endpoints cover chat completions (proxying upstream backends like Ollama or OpenAI-compatible servers), models, prompts, knowledge bases, files, RAG, users, auth, and tools. Authentication uses the Open WebUI session token or per-user API keys. The base URL is wherever you deploy Open WebUI (commonly http://localhost:3000/api/v1).
- **Base URL:** `http://localhost:3000/api/v1`
- **Docs:** https://docs.openwebui.com/

## Common Properties
- [Website](https://openwebui.com/)
- [Developer Portal](https://docs.openwebui.com/)
- [OpenSource](https://github.com/open-webui/open-webui)
- [Plans](plans/open-webui-plans-pricing.yml) — reconciled (free OSS; self-host)
- [RateLimits](rate-limits/open-webui-rate-limits.yml) — reconciled (no built-in cap; upstream backend limits apply)
- [FinOps](finops/open-webui-finops.yml) — reconciled (FOCUS-aligned)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
