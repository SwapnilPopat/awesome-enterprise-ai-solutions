# Awesome Enterprise AI Solutions

A curated, production-ready collection of enterprise AI frameworks, LLM tools, RAG patterns, and agentic AI solutions. Focused on open-source projects suitable for enterprise deployments with emphasis on scalability, governance, and cost optimization.

---

## Enterprise LLM Frameworks

- **[LLMware](https://github.com/llmware-ai/llmware)** - Unified framework for enterprise RAG pipelines with small, specialized models
- **[LangChain](https://github.com/langchain-ai/langchain)** - Industry-standard framework for building LLM applications
- **[LlamaIndex](https://github.com/run-llama/llama_index)** - Data framework for connecting private data to LLMs

## RAG & Knowledge Systems

- **[Haystack](https://github.com/deepset-ai/haystack)** - LLM orchestration framework for RAG and QA systems
- **[QdrantCE](https://github.com/qdrant/qdrant)** - Vector database for similarity search
- **[Weaviate](https://github.com/weaviate/weaviate)** - Vector database optimized for NLP pipelines
- **[Jina](https://github.com/jina-ai/jina)** - Multi-modal AI framework

## Orchestration & MLOps

- **[Apache Airflow](https://github.com/apache/airflow)** - Workflow orchestration platform
- **[Prefect](https://github.com/PrefectHQ/prefect)** - Modern workflow orchestration and ML Model Serving
- **[VLLM](https://github.com/vllm-project/vllm)** - Fast LLM serving
- **[BentoML](https://github.com/bentoml/BentoML)** - ML model serving framework
- **[Seldon Core](https://github.com/SeldonIO/seldon-core)** - Model serving on Kubernetes

## Data Governance

- **[Great Expectations](https://github.com/great-expectations/great_expectations)** - Data validation framework
- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)** - Metadata management platform
- **[Langfuse](https://github.com/langfuse/langfuse)** - LLM observability and monitoring
- **[Prometheus](https://prometheus.io/)** - Metrics and monitoring

## Learning & Implementation

- **[LLMs from Scratch](https://github.com/rasbt/LLMs-from-scratch)** - LLM implementation guide
- **[Awesome LLM Agents](https://github.com/kaushikjadhav01/awesome-llm-agents)** - LLM agent framework

---

## 🚀 Starter Open-Source AI Tutorials

Beginner-friendly, hands-on tutorials for learning open-source AI. Perfect for those new to LLMs and enterprise AI.

| Tutorial | Description | Folder |
|----------|-------------|--------|
| **Local Chatbot with Llama/Qwen + LangChain** | Build a simple conversational AI running locally | [`starter_open_source_ai/local_llm_chatbot`](./starter_open_source_ai/local_llm_chatbot) |
| **Simple RAG over PDFs** | Extract insights from documents using open-source RAG | [`starter_open_source_ai/rag_over_pdfs`](./starter_open_source_ai/rag_over_pdfs) |
| **Basic REST API Agent** | Create an AI agent that calls external APIs | [`starter_open_source_ai/basic_rest_agent`](./starter_open_source_ai/basic_rest_agent) |
| **Batch Inference Pipeline** | Schedule and run inference with Airflow + vLLM | [`starter_open_source_ai/batch_inference_pipeline`](./starter_open_source_ai/batch_inference_pipeline) |

### Getting Started

1. **Clone the repository:**
2.    ```bash
         git clone https://github.com/SwapnilPopat/awesome-enterprise-ai-solutions.git
         cd awesome-enterprise-ai-solutions
         ```

      2. **Choose a starter tutorial:**
      3.    Pick any folder from the table above based on your learning goal.
  
      4.3. **Install dependencies:**
     ```bash
     cd starter_open_source_ai/local_llm_chatbot  # or your chosen tutorial
     pip install -r requirements.txt
     ```

  4. **Set up environment:**
  5.    ```bash
           cp .env.example .env
           # Edit .env with your configuration (optional for local-only setups)
           ```

        5. **Run the example:**
        6.    ```bash
                 python main.py
                 ```

              ---

## 📀 Enterprise RAG Patterns (Open Source)

----------------------------------------

Production-ready RAG implementations using open-source vector databases and frameworks.

| Pattern                         | Stack                      | Folder                                                                     |
|---------------------------------|----------------------------|----------------------------------------------------------------------------
| **Local RAG with Llama 3 + Qdrant** | Llama 3, Qdrant, LangChain | [`enterprise_rag_patterns/local_rag_llama_qdrant`](./enterprise_rag_patterns/local_rag_llama_qdrant) |
| **Hybrid Search RAG** | Weaviate/Qdrant, Haystack | [`enterprise_rag_patterns/hybrid_search_rag`](./enterprise_rag_patterns/hybrid_search_rag) |
| **RAG-as-a-Service** | FastAPI, Docker, LlamaIndex | [`enterprise_rag_patterns/rag_as_a_service`](./enterprise_rag_patterns/rag_as_a_service) |

    ---

## 📋‍🎛 Enterprise AI Agent Recipes

Real-world AI agent patterns for enterprise workflows—all built with open-source tools.

| Agent                        | Use Case                                           | Stack                 | Folder                                                                 |
|------------------------------|----------------------------------------------------|-----------------------|------------------------------------------------------------------------|
| **System Architecture Agent** | Generate infrastructure diagrams & recommendations | LangChain, Claude | [`enterprise_ai_agents/system_architect_agent`](./enterprise_ai_agents/system_architect_agent) |
| **Incident Triage Agent** | Analyze logs and alerts, suggest remediation | Haystack, vLLM | [`enterprise_ai_agents/incident_triage_agent`](./enterprise_ai_agents/incident_triage_agent) |
| **Requirements Drafting Agent** | Convert user stories into formal PRDs/BRDs | LangChain, LlamaIndex | [`enterprise_ai_agents/requirements_agent`](./enterprise_ai_agents/requirements_agent) |

    ---
    

## Contributing

Contributions welcome! Submit PRs with project name, description, category, and your use case.

---

## License

MIT License
