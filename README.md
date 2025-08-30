# rag-persona-benchmark

## 🧠 Overview
This project explores how **Retrieval-Augmented Generation (RAG)** can be leveraged to create and evaluate AI personas.  
By grounding large language model outputs in persona-specific knowledge, we assess how effectively AI agents can mimic roles such as **journalists** or **researchers** while maintaining factual accuracy and stylistic consistency.

---

## 🎯 Goals
- **Persona Simulation** → Generate responses that reflect the behavior and tone of different personas  
- **Knowledge Grounding** → Use RAG to ensure outputs are tied to persona-relevant context  
- **Comparative Evaluation** → Measure how journalist and researcher personas differ in style, accuracy, and depth  

---

## 📂 Project Layout
- **/context_files/** → Persona-specific documents used for grounding  
- **/notebooks/** → Jupyter notebooks for experimentation and analysis  
- **/scripts/** → Core pipeline for loading data, embedding, retrieval, and persona evaluation  
- **/results/** → Saved outputs, comparisons, and evaluation metrics  

---

## 🔧 Key Components
- **Retrieval-Augmented Generation (RAG)** → Ensures responses are context-driven and grounded in facts  
- **Persona Definition** → Context files define traits of journalist vs researcher roles  
- **Evaluation Metrics** → Style adherence, factual correctness, and content quality  

---

## 📊 Example Use Case
1. Define persona context (e.g., *journalist knowledge base*)  
2. Ask a question: *“Summarize today’s economic report.”*  
3. System retrieves relevant passages + generates answer  
   - **Journalist Persona** → Concise, news-style summary  
   - **Researcher Persona** → Analytical, detailed breakdown  

---

## 🚀 Future Extensions
- Add more personas (e.g., policy analyst, teacher, critic)  
- Develop automated persona evaluation metrics  
- Integrate with multi-agent simulations for collaborative tasks  

---
