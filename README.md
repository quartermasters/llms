# 🔒 LLMS – Local Language Model System by Quartermasters

**Privacy-First AI for Startups and Medium Enterprises**

LLMS is an open-core, on-premises AI solution that brings secure large language model inference, private fine-tuning, and RAG (Retrieval-Augmented Generation) to businesses that need full data sovereignty.

Built and maintained by [Quartermasters FZC](https://quartermasters.me), LLMS empowers teams to innovate with AI without sending data to the cloud.

---

## 🎯 Who It's For

- ✅ Startups handling sensitive IP or customer data
- ✅ Medium enterprises with compliance needs (GDPR, HIPAA, FedRAMP)
- ✅ Legal, Finance, Healthcare, Government, and Tech industries
- ✅ Teams seeking air-gapped, GPU-powered LLM environments

---

## 🧩 Core Features

| Feature         | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| **Offline Inference** | Run Mistral, LLaMA 3, Phi-4, or custom models locally                  |
| **Private RAG**       | Embed, index, and query your docs using FAISS/Qdrant + Instructor-XL |
| **Secure SFT**        | Fine-tune models using LoRA/QLoRA with no external API usage          |
| **Admin Console**     | Track sessions, GPU usage, logs, and access roles                     |
| **Pluggable UI**      | Web and Electron-based assistant interface (multi-threaded chat)      |

---

## 🛠️ Tech Stack

- **LLMs**: [Mistral-7B](https://mistral.ai), [LLaMA 3](https://ai.meta.com/llama/), [Phi-4](https://www.microsoft.com/en-us/research/blog/phi-3/), [DeepCoder](https://huggingface.co)
- **RAG**: Instructor-XL / BGE-Large + FAISS / Qdrant
- **Backend**: Ollama, llama.cpp, HuggingFace Transformers, PEFT
- **Database**: PostgreSQL (for logs, configs), SQLite (optional)
- **Containerized**: Docker Compose + NVIDIA GPU support

---

## ⚙️ Quick Start

> 🧠 Requires: Linux or Windows + Docker + NVIDIA GPU (24 GB recommended)

```bash
git clone https://github.com/quartermasters/llms.git
cd llms
docker compose up -d
