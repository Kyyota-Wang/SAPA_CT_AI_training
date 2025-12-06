# AI Agent Demo  
A lightweight demonstration of building AI Agents with Gemini / OpenAI for medical information retrieval.

Author: **Yunlong Wang**

---

## 📘 Overview
This repository contains a minimal but functional prototype of an **AI Agent** that supports:

1. **Standard Chat + Search**  
   Answers medical questions using LLM reasoning and optional external search.

2. **RAG Mode (Excel-Based Retrieval Augmentation)**  
   Leverages `drug_data_large.xlsx` as a structured knowledge source for drug information lookup.

3. **JSON Output Mode**  
   Returns structured, machine-readable responses for downstream applications.

Two Jupyter notebooks are included:

- `agent_naive.ipynb` — baseline agent (chat + search)  
- `agent_w_rag.ipynb` — enhanced agent with Excel RAG capability  

---

## 🧠 Key Features
- Multi-mode interaction: chat mode, RAG queries, and JSON-formatted responses  
- Modular design for easy extension and integration  
- Supports dynamic tool-use logic (search, retrieval, reasoning)  
- Demonstrates how to blend LLM reasoning with structured data sources  

---

## 📂 Project Structure
/
├── agent_naive.ipynb # Basic AI agent (chat + search)
├── agent_w_rag.ipynb # RAG-enabled AI agent using Excel
├── drug_data_large.xlsx # External drug data knowledge source
└── README.md # Project documentation



---

## 🚀 How to Run
1. Open the notebook in **Jupyter**, **VS Code**, or **Google Colab**.  
2. Install dependencies (`google-generativeai`, `pandas`, `openpyxl`, etc.).  
3. Set your API key in the notebook.  
4. Execute all cells to start interacting with the agent.

---
