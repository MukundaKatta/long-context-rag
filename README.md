# Long Context Rag

RAG optimized for 1M+ token contexts with hierarchical retrieval

## Features

- Api
Chunker
Compressor
Context Builder
Embedder
Indexer
Reranker
Retriever

## Tech Stack

- **Language:** Python
- **Framework:** FastAPI
- **Key Dependencies:** pydantic,fastapi,uvicorn,anthropic,openai,numpy
- **Containerization:** Docker + Docker Compose

## Getting Started

### Prerequisites

- Python 3.11+
- Docker & Docker Compose (optional)

### Installation

```bash
git clone https://github.com/MukundaKatta/long-context-rag.git
cd long-context-rag
pip install -r requirements.txt
```

### Running

```bash
uvicorn app.main:app --reload
```

### Docker

```bash
docker-compose up
```

## Project Structure

```
long-context-rag/
├── src/           # Source code
├── tests/         # Test suite
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
└── README.md
```

