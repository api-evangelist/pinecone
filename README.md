# Pinecone (pinecone)

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

With its vector database at the core, Pinecone is the leading knowledge platform for building accurate, secure, and scalable AI applications. The Pinecone APIs cover Database (vector storage and search), Inference (embeddings and reranking), Assistant (RAG over documents), and Admin (organization and project management).

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Vector Databases
- AI
- Embeddings
- RAG

## Timestamps

- **Created:** 2024-07-02
- **Modified:** 2026-04-28

## APIs

### Pinecone Database Control API

Use the Database Control API to manage indexes, collections, and backups in Pinecone Database. The control plane handles lifecycle and configuration of vector storage resources.

- **Human URL:** https://docs.pinecone.io/reference/api/introduction
- **Base URL:** `https://api.pinecone.io`
- [Documentation](https://docs.pinecone.io/reference/api/introduction) | [OpenAPI](openapi/pinecone-db-control-openapi.yaml)

### Pinecone Database Data API

Use the Database Data API to upsert, query, fetch, update, and delete vector records in Pinecone indexes. The data plane is the high-throughput interface for real-time vector search.

- **Human URL:** https://docs.pinecone.io/reference/api/introduction
- **Base URL:** `https://{index_host}`
- [Documentation](https://docs.pinecone.io/reference/api/introduction) | [OpenAPI](openapi/pinecone-db-data-openapi.yaml)

### Pinecone Inference API

Use the Inference API to generate vector embeddings and rerank results using models hosted on Pinecone's infrastructure.

- **Human URL:** https://docs.pinecone.io/reference/api/introduction#inference-api
- **Base URL:** `https://api.pinecone.io`
- [Documentation](https://docs.pinecone.io/reference/api/introduction#inference-api) | [OpenAPI](openapi/pinecone-inference-openapi.yaml)

### Pinecone Assistant Control API

Use the Assistant Control API to create and manage Pinecone Assistants for retrieval-augmented generation (RAG) over your documents.

- **Human URL:** https://docs.pinecone.io/reference/api/introduction#assistant-api
- **Base URL:** `https://api.pinecone.io`
- [Documentation](https://docs.pinecone.io/reference/api/introduction#assistant-api) | [OpenAPI](openapi/pinecone-assistant-control-openapi.yaml)

### Pinecone Assistant Data API

Use the Assistant Data API to upload documents to a Pinecone Assistant, ask questions, and receive responses grounded in those documents.

- **Human URL:** https://docs.pinecone.io/reference/api/introduction#assistant-api
- **Base URL:** `https://prod-1-data.ke.pinecone.io`
- [Documentation](https://docs.pinecone.io/reference/api/introduction#assistant-api) | [OpenAPI](openapi/pinecone-assistant-data-openapi.yaml)

### Pinecone Admin API

Use the Admin API to manage Pinecone organizations, projects, API keys, and service accounts at the platform level.

- **Human URL:** https://docs.pinecone.io/reference/api/introduction
- **Base URL:** `https://api.pinecone.io`
- [Documentation](https://docs.pinecone.io/reference/api/introduction) | [OpenAPI](openapi/pinecone-admin-openapi.yaml)

## Common Properties

- [Website](https://www.pinecone.io/)
- [Pricing](https://www.pinecone.io/pricing/)
- [Blog](https://www.pinecone.io/blog/)
- [Newsroom](https://www.pinecone.io/newsroom/news/)
- [Documentation](https://docs.pinecone.io/guides/get-started/overview)
- [Getting Started](https://docs.pinecone.io/guides/get-started/overview)
- [Features](https://docs.pinecone.io/guides/get-started/key-features)
- [Glossary](https://docs.pinecone.io/guides/get-started/glossary)
- [Examples](https://docs.pinecone.io/examples/notebooks)
- [Integrations](https://docs.pinecone.io/integrations/overview)
- [ChangeLog](https://docs.pinecone.io/release-notes/2024)
- [Status](https://status.pinecone.io/)
- [Login](https://app.pinecone.io)
- [Security](https://www.pinecone.io/security/)
- [Terms of Service](https://www.pinecone.io/legal/)
- [Privacy Policy](https://www.pinecone.io/privacy/)
- [SDKs](https://docs.pinecone.io/reference/pinecone-sdks)
- [Spec Repository](https://github.com/pinecone-io/pinecone-api)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
