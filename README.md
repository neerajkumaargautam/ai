# AI: Zero to Expert (🚧 In Progress)

A structured, hands-on repository covering Artificial Intelligence engineering from classical machine learning and deep learning to Generative AI, Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), Agentic AI, and enterprise `.NET` AI integration.

## Module Roadmap

### Phase 1: Foundations & Machine Learning Core (`01` – `05`)
| # | Module | Key Topics (AI & Enterprise .NET Focus) |
| :--- | :--- | :--- |
| [00](./00-python-fundamentals/README.md) | Python Programming Fundamentals  |
| [01](./01-python-and-data-science/README.md) | Python for AI & Data Science | Python asynchronous programming, NumPy, Pandas, data wrangling, and data pipeline preparation |
| [02](./02-classical-machine-learning/README.md) | Classical Machine Learning | Scikit-learn, regression, classification, clustering algorithms, model evaluation metrics, and pipeline serialization |
| [03](./03-deep-learning-fundamentals/README.md) | Deep Learning Fundamentals | Neural network architecture, PyTorch tensors, backpropagation, activation functions, and gradient descent optimizers |
| [04](./04-nlp-and-text-preprocessing/README.md) | NLP & Text Preprocessing | Tokenization, text normalization, TF-IDF, semantic similarity, and dense word embeddings (Word2Vec, GloVe) |
| [05](./05-transformers-and-attention/README.md) | Transformers & Attention Mechanisms | Self-attention mechanics, encoder-decoder architecture, Hugging Face `transformers` library, and tokenizers |

---

### Phase 2: LLMs, Prompt Engineering & Fine-Tuning (`06` – `10`)
| # | Module | Key Topics (AI & Enterprise .NET Focus) |
| :--- | :--- | :--- |
| [06](./06-llm-landscape-and-inference/README.md) | LLM Landscape & Model Inference | Foundation models, open-source vs. proprietary LLMs, token limits, context windows, and API inference parameters |
| [07](./07-prompt-engineering-and-guardrails/README.md) | Prompt Engineering & Guardrails | Zero-shot/few-shot prompting, Chain-of-Thought (CoT), system prompts, structured JSON outputs, and safety guardrails |
| [08](./08-fine-tuning-and-adaptation/README.md) | Fine-Tuning & Model Adaptation | Parameter-Efficient Fine-Tuning (PEFT), LoRA, QLoRA, dataset curation, and Supervised Fine-Tuning (SFT) |
| [09](./09-vector-databases-and-embeddings/README.md) | Vector Databases & Embeddings | Embedding generation models, vector similarity metrics (Cosine, L2, Dot Product), Qdrant, Chroma, and Azure AI Search |
| [10](./10-rag-architecture-and-pipelines/README.md) | Retrieval-Augmented Generation (RAG) | Advanced RAG pipelines, chunking strategies, semantic search, hybrid retrieval, re-ranking, and hallucination reduction |

---

### Phase 3: Agentic AI, MCP & Enterprise Integration (`11` – `15`)
| # | Module | Key Topics (AI & Enterprise .NET Focus) |
| :--- | :--- | :--- |
| [11](./11-agentic-ai-workflows/README.md) | Agentic AI & Autonomous Workflows | ReAct pattern, tool use, function calling, planning loops, and autonomous task execution frameworks |
| [12](./12-model-context-protocol-mcp/README.md) | Model Context Protocol (MCP) | Anthropic MCP architecture, client-server communication, transport layers, and custom tool/resource servers |
| [13](./13-semantic-kernel-dotnet-integration/README.md) | Semantic Kernel & .NET AI Integration | Microsoft Semantic Kernel, plugins, native functions, prompt templates, planners, and C# agentic patterns |
| [14](./14-azure-openai-enterprise-deployment/README.md) | Azure OpenAI & Enterprise Deployment | Azure OpenAI Service, deployment quotas, content safety filters, private networking, and semantic caching |
| [15](./15-ai-evaluation-and-observability/README.md) | AI Evaluation & Observability | RAG triad evaluation (faithfulness, answer relevance), Promptfoo testing, and OpenTelemetry tracing for LLM apps |

---

### Phase 4: Advanced Architectures & Capstone (`16` – `18`)
| # | Module | Key Topics (AI & Enterprise .NET Focus) |
| :--- | :--- | :--- |
| [16](./16-multi-agent-systems/README.md) | Multi-Agent Systems | Collaborative agent networks, state management, hierarchical delegation, and multi-agent problem solving |
| [17](./17-local-llms-and-quantization/README.md) | Local LLMs, Quantization & Edge AI | GGUF, AWQ quantization formats, running local open-source models via Ollama and vLLM |
| [18](./18-capstone-enterprise-ai-solution/README.md) | Capstone: Enterprise AI-Powered .NET Solution | End-to-end production AI architecture: **.NET 8 Web API + Semantic Kernel + Vector DB + RAG + MCP Tool Integration** |

---

## Tech Stack Covered
- **Languages & Frameworks:** Python, C#, .NET 8, Microsoft Semantic Kernel, PyTorch, Hugging Face
- **AI & LLM Ecosystem:** Azure OpenAI, OpenAI API, Anthropic Claude, Ollama, vLLM, LangChain/LlamaIndex concepts
- **Vector & Data Stores:** Qdrant, Chroma, Azure AI Search, Azure SQL
- **Protocols & Architecture:** Model Context Protocol (MCP), Retrieval-Augmented Generation (RAG), Agentic Workflows, OpenTelemetry

Status labels: ⏳ Yet to start, 🚧 In Progress, or ✅ Completed
