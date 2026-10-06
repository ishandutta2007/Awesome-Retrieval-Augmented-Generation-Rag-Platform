# 🚀 Awesome Retrieval-Augmented Generation (RAG) Platform Ecosystem

![Awesome RAG Platforms Banner](./assets/banner.svg)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Retrieval-Augmented-Generation-Rag-Platform/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Retrieval-Augmented-Generation-Rag-Platform?style=social" alt="Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Retrieval-Augmented-Generation-Rag-Platform/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Retrieval-Augmented-Generation-Rag-Platform?style=social" alt="Forks"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 💡 Overview & Ecosystem Insights

Welcome to the **Curated Guide to Retrieval-Augmented Generation (RAG) Platforms, Managed Vector Engines, and Open-Source RAG Infrastructure**. 

This repository tracks notable **commercial RAG platforms**, **managed vector databases**, and **open-source RAG frameworks** that connect Large Language Models (LLMs) to private enterprise data, unstructured documents, and API knowledge repositories—enabling grounded, hallucination-free, cited, and accurate AI responses.

### 🌐 Market Size & Industry Structure
> 📊 **Estimated Market Size**: The global Retrieval-Augmented Generation (RAG) and Enterprise Search market is estimated at **$2.5 Billion in 2026** and is projected to reach **$11.8 Billion by 2030** (CAGR ~47%).  
> 🧩 **Market Fragmentation**: The sector is **moderately to highly fragmented**. While hyperscalers (AWS Bedrock Knowledge Bases) and specialized vector database leaders (Pinecone, Qdrant, Weaviate) capture enterprise storage workloads, open-source orchestration engines (Dify, LangChain, LlamaIndex, RAGFlow) prevent a single "winner-take-all" outcome by giving developers sovereignty over document processing, embedding, and hybrid retrieval.

---

## 📑 Table of Contents
- [🏢 SaaS & Managed RAG Platforms](#-saas--managed-rag-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [💖 Support](#-support)
- [⚠️ Disclaimer](#️-disclaimer)
- [⭐ Star History](#-star-history)

---

## 🏢 SaaS & Managed RAG Platforms

Below is a curated selection of commercial and fully managed RAG platforms, vector databases, and enterprise document ingestion services, **sorted by Company Scale (Valuation / Revenue in Descending Order)**:

| Platform / Service | Scale / Valuation / Revenue | Starting Paid Tier Pricing | Free Tier / Trial Limits | Key Use Case & Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Amazon Bedrock Knowledge Bases](https://aws.amazon.com/bedrock/knowledge-bases/)** | **~$1.8 Trillion (AWS Parent Market Cap)** | $0.10 per GB/month storage + $0.0001 per retrieval API call | AWS Free Tier: 2,000 free retrieval queries/month for 12 months | **Best for AWS-native RAG**: Fully managed document chunking, embedding, vector storage, and foundation model generation. |
| **[Pinecone](https://www.pinecone.io/)** | **$750 Million Valuation** | $50/month (Standard plan) | Free Starter Plan: 1 project, 1 index, up to 100k vectors (2GB storage) | **Best for vector search at scale**: Leading enterprise managed vector database with serverless indexing and hybrid search. |
| **[Glean](https://www.glean.com/)** | **$4.6 Billion Valuation** | $12/user/month (Enterprise packages) | 30-day Enterprise Free Trial for up to 50 users | **Best for enterprise knowledge**: Permission-aware generative search and RAG across company SaaS suites (Slack, Jira, Google Drive). |
| **[Qdrant Cloud](https://qdrant.tech/)** | **$280 Million Valuation** | $25/month (Cluster tier) | Free Forever Cluster: 1GB cluster storage (~100k vectors) | **Best for high-performance vector search**: Managed Rust-based vector search engine with payload filtering. |
| **[Weaviate Cloud](https://weaviate.io/)** | **$200 Million Valuation** | $25/month (Serverless tier) | $100 Free Credit for 14-day Sandbox Cluster | **Best for AI-native applications**: Vector database with GraphQL API, hybrid BM25 search, and multi-modal embeddings. |
| **[Unstructured](https://unstructured.io/)** | **$200 Million Valuation** | $10/1,000 pages processed | 14-day Free Trial with 1,000 free document pages | **Best for document processing**: Ingests, cleans, and partitions complex PDFs, slides, tables, and scanned docs into RAG-ready JSON. |
| **[LlamaIndex Cloud](https://www.llamaindex.ai/)** | **$80 Million Valuation** | $50/month (Developer plan) | Free Tier: 1,000 document parses/month + 10k retrieval queries/month | **Best for developer-friendly RAG**: Managed document parsing (LlamaParse), indexing workflows, and advanced retrieval APIs. |
| **[Chroma Cloud](https://www.trychroma.com/)** | **$75 Million Valuation** | $20/month (Managed Hosted) | Free Tier: 50,000 vectors & 1GB hosted index storage | **Best for rapid RAG prototypes**: AI-native embedding database for fast Python/JS application integration. |
| **[Dify Knowledge](https://dify.ai/)** | **$50 Million Valuation** | $59/month (Professional plan) | Free Sandbox: 200 GPT/LLM call credits & 5MB document upload limit | **Best for visual RAG development**: Cloud-hosted visual orchestration platform with built-in document management. |
| **[Ragie](https://www.ragie.ai/)** | **$15 Million Valuation** | $29/month (Starter tier) | Free Tier: 100 document uploads & 1,000 search queries/month | **Best for rapid RAG development**: Fully managed RAG-as-a-service providing instant chunking, embedding, and retrieval APIs. |

---

## 🔓 Open-Source GitHub Projects

The open-source RAG ecosystem offers complete self-hosted platforms, modular frameworks, vector search engines, and document parsers. Below is a comprehensive list **sorted by GitHub Stars_Count (Descending)**, with social badges linking directly to each repository's stargazers page:

### 🌟 Top Open-Source RAG Ecosystem (Sorted by Stars)

- **[Dify](https://github.com/langgenius/dify)** [![GitHub_Stars](https://img.shields.io/github/stars/langgenius/dify?style=social&color=white)](https://github.com/langgenius/dify/stargazers)  
  **The leading open-source LLM app development platform** (Apache-2.0). Features a visual workflow builder for RAG pipelines, AI agents, and prompt orchestration with built-in document ingestion and hybrid retrieval.

- **[LangFlow](https://github.com/langflow-ai/langflow)** [![GitHub_Stars](https://img.shields.io/github/stars/langflow-ai/langflow?style=social&color=white)](https://github.com/langflow-ai/langflow/stargazers)  
  **Visual framework for building multi-agent RAG applications** (MIT). Drag-and-drop canvas for composing vector search, document chunking, and custom retriever components.

- **[Open WebUI](https://github.com/open-webui/open-webui)** [![GitHub_Stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social&color=white)](https://github.com/open-webui/open-webui/stargazers)  
  **User-friendly self-hosted Web UI for LLMs and RAG** (MIT). Integrated document upload, hybrid vector search, Ollama support, and granular multi-user permissions.

- **[LangChain](https://github.com/langchain-ai/langchain)** [![GitHub_Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=social&color=white)](https://github.com/langchain-ai/langchain/stargazers)  
  **The standard framework for LLM application development** (MIT). Offers comprehensive RAG chains, document loaders, vector store abstractions, and agentic retrieval.

- **[RAGFlow](https://github.com/infiniflow/ragflow)** [![GitHub_Stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=social&color=white)](https://github.com/infiniflow/ragflow/stargazers)  
  **Open-source RAG engine based on deep document understanding** (Apache-2.0). Features template-based PDF parsing, visual grounding citations, and hallucination reduction.

- **[GPT4All](https://github.com/nomic-ai/gpt4all)** [![GitHub_Stars](https://img.shields.io/github/stars/nomic-ai/gpt4all?style=social&color=white)](https://github.com/nomic-ai/gpt4all/stargazers)  
  **Privacy-aware desktop client with LocalDocs RAG capability** (MIT). Chat with local files and PDFs completely offline on consumer CPUs/GPUs.

- **[Docling](https://github.com/docling-project/docling)** [![GitHub_Stars](https://img.shields.io/github/stars/docling-project/docling?style=social&color=white)](https://github.com/docling-project/docling/stargazers)  
  **IBM Research document processing framework for RAG** (MIT). Converts complex PDFs, scans, and tables into cleanly structured Markdown and JSON.

- **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)** [![GitHub_Stars](https://img.shields.io/github/stars/Mintplex-Labs/anything-llm?style=social&color=white)](https://github.com/Mintplex-Labs/anything-llm/stargazers)  
  **All-in-one desktop and enterprise RAG application** (MIT). Chat with documents, web pages, and databases with workspace isolation and zero-setup vector databases.

- **[Flowise](https://github.com/FlowiseAI/Flowise)** [![GitHub_Stars](https://img.shields.io/github/stars/FlowiseAI/Flowise?style=social&color=white)](https://github.com/FlowiseAI/Flowise/stargazers)  
  **Open-source UI visual tool to build LangChain RAG flows** (Apache-2.0). Build custom document QA pipelines via node-based visual drag-and-drop.

- **[LlamaIndex](https://github.com/run-llama/llama_index)** [![GitHub_Stars](https://img.shields.io/github/stars/run-llama/llama_index?style=social&color=white)](https://github.com/run-llama/llama_index/stargazers)  
  **Data framework for LLM & RAG applications** (MIT). The reference code-first framework for data connectors, advanced chunking, indexing, and reranking retrieval.

- **[Milvus](https://github.com/milvus-io/milvus)** [![GitHub_Stars](https://img.shields.io/github/stars/milvus-io/milvus?style=social&color=white)](https://github.com/milvus-io/milvus/stargazers)  
  **Cloud-native vector database built for scale** (Apache-2.0). Handles multi-billion vector datasets with high throughput and horizontal scalability.

- **[Marker](https://github.com/VikParuchuri/marker)** [![GitHub_Stars](https://img.shields.io/github/stars/VikParuchuri/marker?style=social&color=white)](https://github.com/VikParuchuri/marker/stargazers)  
  **Fast, accurate PDF to Markdown converter** (GPL-3.0). Extracts formulas, tables, and images for clean RAG ingestion.

- **[Quivr](https://github.com/QuivrHQ/quivr)** [![GitHub_Stars](https://img.shields.io/github/stars/QuivrHQ/quivr?style=social&color=white)](https://github.com/QuivrHQ/quivr/stargazers)  
  **Open-source personal RAG second brain** (Apache-2.0). Dump files, notes, and links to query with local or cloud LLMs.

- **[Khoj](https://github.com/khoj-ai/khoj)** [![GitHub_Stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=social&color=white)](https://github.com/khoj-ai/khoj/stargazers)  
  **Open-source AI desktop search assistant** (AGPL-3.0). RAG search across personal notes, PDF documents, and web search.

- **[Microsoft GraphRAG](https://github.com/microsoft/graphrag)** [![GitHub_Stars](https://img.shields.io/github/stars/microsoft/graphrag?style=social&color=white)](https://github.com/microsoft/graphrag/stargazers)  
  **Knowledge graph-driven RAG system by Microsoft** (MIT). Extracts entity-relation knowledge graphs from complex text corpora for global analytical queries.

- **[Qdrant](https://github.com/qdrant/qdrant)** [![GitHub_Stars](https://img.shields.io/github/stars/qdrant/qdrant?style=social&color=white)](https://github.com/qdrant/qdrant/stargazers)  
  **High-performance Rust vector database** (Apache-2.0). Vector search engine with rich payload filtering and fast distance metrics.

- **[Onyx (formerly Danswer)](https://github.com/onyx-dot-app/onyx)** [![GitHub_Stars](https://img.shields.io/github/stars/onyx-dot-app/onyx?style=social&color=white)](https://github.com/onyx-dot-app/onyx/stargazers)  
  **Open-source enterprise search and conversational RAG platform** (MIT). Direct connectors to Slack, Google Drive, Notion, GitHub, and Confluence.

- **[Chroma](https://github.com/chroma-core/chroma)** [![GitHub_Stars](https://img.shields.io/github/stars/chroma-core/chroma?style=social&color=white)](https://github.com/chroma-core/chroma/stargazers)  
  **AI-native embedding database** (Apache-2.0). Simple developer API focused on fast prototyping and local embedding storage.

- **[Haystack](https://github.com/deepset-ai/haystack)** [![GitHub_Stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=social&color=white)](https://github.com/deepset-ai/haystack/stargazers)  
  **Production-ready Python RAG framework by deepset** (Apache-2.0). Modular pipelines for semantic search, question answering, and hybrid reranking.

- **[Pgvector](https://github.com/pgvector/pgvector)** [![GitHub_Stars](https://img.shields.io/github/stars/pgvector/pgvector?style=social&color=white)](https://github.com/pgvector/pgvector/stargazers)  
  **Open-source vector similarity search extension for PostgreSQL** (PostgreSQL License). Enables vector embeddings directly inside existing Postgres tables.

- **[Weaviate](https://github.com/weaviate/weaviate)** [![GitHub_Stars](https://img.shields.io/github/stars/weaviate/weaviate?style=social&color=white)](https://github.com/weaviate/weaviate/stargazers)  
  **Open-source vector database with hybrid search** (BSD-3-Clause). Built-in ML vectorizers, GraphQL interface, and inverted index BM25 integration.

- **[RAGAS](https://github.com/explodinggradients/ragas)** [![GitHub_Stars](https://img.shields.io/github/stars/explodinggradients/ragas?style=social&color=white)](https://github.com/explodinggradients/ragas/stargazers)  
  **Evaluation framework for RAG pipelines** (Apache-2.0). Provides quantitative metrics for context relevance, faithfulness, and answer correctness.

- **[Unstructured](https://github.com/Unstructured-IO/unstructured)** [![GitHub_Stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured?style=social&color=white)](https://github.com/Unstructured-IO/unstructured/stargazers)  
  **Open-source document pre-processing library** (Apache-2.0). Ingests raw documents (PDF, DOCX, PPTX) into structured text elements.

- **[PyMuPDF](https://github.com/pymupdf/PyMuPDF)** [![GitHub_Stars](https://img.shields.io/github/stars/pymupdf/PyMuPDF?style=social&color=white)](https://github.com/pymupdf/PyMuPDF/stargazers)  
  **High-performance C/Python library for PDF text extraction** (AGPL-3.0). Lightning-fast parsing of PDF text, images, and metadata for RAG.

- **[Verba](https://github.com/weaviate/Verba)** [![GitHub_Stars](https://img.shields.io/github/stars/weaviate/Verba?style=social&color=white)](https://github.com/weaviate/Verba/stargazers)  
  **Open-source RAG chatbot powered by Weaviate** (BSD-3-Clause). User interface for document indexing, semantic search, and customizable chunking strategies.

- **[Apache Tika](https://github.com/apache/tika)** [![GitHub_Stars](https://img.shields.io/github/stars/apache/tika?style=social&color=white)](https://github.com/apache/tika/stargazers)  
  **Universal content detection and text extraction toolkit** (Apache-2.0). Detects and extracts text metadata from over 1,000 distinct file formats.

---

## 🛠️ How to Contribute

Contributions from AI engineers and open-source contributors are welcome!
1. **Fork** this repository.
2. Add or update entries in `README.md` keeping descriptions factual, concise, and linked.
3. Ensure open-source additions include Stars_Badges pointing to their repo stargazers URL.
4. Submit a **Pull Request** with a brief summary of additions.

---

## 💖 Support

Thank you for exploring and utilizing the **Awesome RAG Platform Ecosystem** repository! Building and maintaining this open-source resource for AI developers and enterprise architects requires continuous curation.

If you find this list helpful, please consider supporting the project:
- ⭐ **Star** this repository to increase visibility for other AI engineers.
- 🔀 **Fork** and share it with your team and technical network.
- ☕ **Sponsor / Buy Me a Coffee**: If you'd like to support ongoing updates and open-source maintenance, consider sponsoring on GitHub:  
  [![Sponsor](https://img.shields.io/badge/Sponsor-GitHub-ea4aaa?style=for-the-badge&logo=github-sponsors)](https://github.com/sponsors/ishandutta2007)

---

## ⚠️ Disclaimer

- This is a community-curated collection intended for educational and architectural evaluation purposes.
- RAG accuracy and security depend on vector retrieval configuration, embedding quality, chunking strategy, and tenant isolation controls. Evaluate thoroughly using frameworks like RAGAS before pushing to production.

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Retrieval-Augmented-Generation-Rag-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Retrieval-Augmented-Generation-Rag-Platform&type=date&legend=top-left)

---

<p align="center">
  <b>Maintained by <a href="https://github.com/ishandutta2007">ishandutta2007</a> for AI developers, system architects, and RAG practitioners.</b>
</p>
