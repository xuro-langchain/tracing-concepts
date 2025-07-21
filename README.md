# LangSmith Tracing Concepts

This repository contains comprehensive tutorials and examples for implementing tracing in LLM applications using LangSmith. The notebooks demonstrate various approaches to tracing, from basic implementations to advanced distributed tracing scenarios.


### Installation

1. Clone this repository:
```bash
git clone https://github.com/xuro-langchain/tracing-concepts
cd tracing-concepts
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
Create a `.env` file in the root directory using `.env.example` as guidance

## 📖 Notebooks

### 1. Basic Tracing (`notebooks/basic_tracing.ipynb`)

In this notebook, we:
- Set up a simple RAG (Retrieval Augmented Generation) application
- Trace the application using the `@traceable` decorator
- Implement the same concept using LangGraph


### 2. Advanced Tracing (`notebooks/advanced_tracing.ipynb`)

In this notebook, we:
- Use the `trace` context manager for fine-grained control
- Use `RunTree` API for advanced manual tracing


### 3. Distributed Tracing (`notebooks/distributed_tracing.ipynb`)

In this notebook, we:
- Implement tracing across different systems and processes
- Using trace headers to maintain context across distributed calls


### 4. Tracing Metadata (`notebooks/tracing_metadata.ipynb`)

In this notebook, we:
- Add metadata and tags to your traces
- Query and filter traces using metadata