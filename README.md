# AI Tech Marketplace — AI Service

AI service for intelligent shopping functionality.

## Technology

* Python
* FastAPI
* Embeddings
* RAG
* Recommendation algorithms
* LLM APIs

## Responsibilities

The AI service provides:

* AI Shopping Assistant
* Semantic search
* Product recommendation
* Product comparison
* RAG
* LLM integration

## Architecture

```text
Spring Boot
     |
     | Internal API
     v
Python FastAPI
     |
     ├── Retrieval
     ├── Embedding
     ├── Recommendation
     └── LLM
```

## Important Rule

The AI service does not own transactional marketplace data.

The Spring Boot backend remains the source of truth for:

* Products
* Prices
* Inventory
* Orders
* Users

## Development

Local development instructions will be added during Phase 3.
