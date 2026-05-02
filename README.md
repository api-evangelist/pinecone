# Pinecone (pinecone)

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
