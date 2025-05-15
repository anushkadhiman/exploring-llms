# Exploring LLMs

Welcome to **`exploring-llms`** — a personal journey into the evolving world of **Large Language Models (LLMs)**.  
This repository contains hands-on notebooks experimenting with different LLM use cases, architectures, and tooling — starting with **local LLMs** and expanding into broader applications over time.

---

## 🧪 Current Experiments

### 📄 `Build_a_simple_LLM_system_locally_Langchain_LlamaCPP.ipynb` [Full article]((https://sotainsights.substack.com/p/build-a-simple-llm-system-locally)) 
- Running a local LLM using [`llama.cpp`](https://github.com/ggerganov/llama.cpp)
- Building a basic LangChain-powered pipeline
- Exploring prompt-based interactions **without using APIs**

### 📄 `Build_a_simple_LLM_system_locally_overPDF_Langchain_LlamaCPP.ipynb` [Full article]((https://github.com/anushkadhiman/exploring-llms/blob/main/Build_a_simple_LLM_system_locally_overPDF_Langchain_LlamaCPP.ipynb))
- Creating a semantic search engine over a PDF
- Using LangChain document loaders, text splitters, and Chroma vector store
- Embedding with SentenceTransformers or Llama-based models
- Querying the document with a retrieval-augmented QA system

---

## 🎯 Goals of This Repo

- Explore trends and tools in the LLM space (local, cloud, open, proprietary)
- Understand practical use cases like semantic search, RAG, and assistants
- Experiment with LLM stacks like **LangChain**, **LlamaCPP**, **Chroma**, **OpenRouter**, and more
- Stay adaptable to new models and approaches as the space evolves

---

## 📝 Read the Full Articles

I’m also documenting my learnings and tutorials as articles on **Substack** and **Medium**.  
Check them out for deeper explanations and step-by-step guides:

- 📬 [My Substack]([https://your-substack-link](https://sotainsights.substack.com/))  
- ✍️ [My Medium]([https://your-medium-link](https://anushkadhiman.medium.com/))

---

## 🚀 Setup

Install dependencies with:
pip install -r requirements.txt


Make sure to download any required LLM models locally if running offline (e.g., .gguf files for llama.cpp).

Launch Jupyter and start exploring:
jupyter notebook

