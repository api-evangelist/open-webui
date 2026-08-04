# Open WebUI (open-webui)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Open WebUI is a self-hosted, open-source web UI for LLMs (notably Ollama and OpenAI-compatible backends). It exposes a REST API for chats, models, prompts, knowledge (RAG), users, and tools. Distributed under a modified BSD-3-Clause license; primarily run via Docker or pip on your own infrastructure.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/open-webui/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/open-webui/refs/heads/main/apis.yml)

## Tags

- LLM
- Open Source
- Self-Hosted
- Ollama
- Chat UI
- RAG

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Open WebUI API

REST API exposed by a self-hosted Open WebUI instance. Endpoints cover chat completions (proxying upstream backends like Ollama or OpenAI-compatible servers), models, prompts, knowledge bases, files, RAG, users, auth, and tools. Authentication uses the Open WebUI session token or per-user API keys. The base URL is wherever you deploy Open WebUI (commonly http://localhost:3000/api/v1).

- **Human URL:** [https://docs.openwebui.com/getting-started/api-endpoints](https://docs.openwebui.com/getting-started/api-endpoints)
- **Base URL:** `http://localhost:3000/api/v1`

#### Tags

- Chat
- Models
- Prompts
- RAG
- Knowledge
- Tools

#### Properties

- [Documentation](https://docs.openwebui.com/)
- [Git Hub](https://github.com/open-webui/open-webui)
- [Reference](https://docs.openwebui.com/getting-started/api-endpoints)
- [Postman Collection](collections/open-webui.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/open-webui.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/open-webui)
- [Website](https://openwebui.com/)
- [Developer Portal](https://docs.openwebui.com/)
- [Open Source](https://github.com/open-webui/open-webui)
- [Plans](plans/open-webui-plans-pricing.yml)
- [Rate Limits](rate-limits/open-webui-rate-limits.yml)
- [Fin Ops](finops/open-webui-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
