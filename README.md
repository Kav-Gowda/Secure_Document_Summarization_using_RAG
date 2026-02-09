# Secure Document Summarization using RAG

A **Retrieval-Augmented Generation (RAG)** agent that summarizes and answers questions over private documents using **IBM watsonx.ai**, **LangChain**, and **Llama 3.3**.  
This project demonstrates how to build an intelligent assistant that retrieves, summarizes, and converses over confidential text — without exposing data to third parties.

---

## 🚀 Project Overview
In an age of information overload, this project enables **secure document understanding** by combining powerful large language models with retrieval pipelines.  
The agent can:
- Split and embed private text documents
- Store embeddings in a **ChromaDB** vector store
- Retrieve and summarize relevant sections using **LangChain RAG**
- Maintain conversational memory for multi-turn interactions

---

## 🧩 Tech Stack
- **LLM Platform:** IBM watsonx.ai  
- **Frameworks:** LangChain, Chroma  
- **Embeddings:** HuggingFace Sentence Transformers  
- **Model:** Llama 3.3 (via watsonx.ai)  
- **Notebook Environment:** Google Colab  
- **Language:** Python  

---

## 📂 Project Structure
watsonx-rag-agent/
├── .gitignore
├── LICENSE
├── README.md
├── notebooks/
│ └── watsonx_rag_agent.ipynb
└── data/ (not included – private documents)


---

## ⚙️ How It Works
1. Load and preprocess private text documents  
2. Split documents into chunks using `CharacterTextSplitter`  
3. Create embeddings with `HuggingFaceEmbeddings`  
4. Store embeddings and perform retrieval via **ChromaDB**  
5. Query the LLM (Granite or Llama 3.3) through **LangChain RAG**  
6. Maintain memory using `ConversationBufferMemory`  
7. Interact with the agent for contextual, multi-turn Q&A  

---

## 🧠 Key Features
- **Private document summarization**  
- **Retrieval-Augmented Q&A**  
- **Conversational context retention**  
- **Watsonx.ai integration with LangChain**  

---

## 🔒 Data Privacy
This project is designed for **private and local document handling**.  
All API keys and document data are excluded from the repository for confidentiality.

---

## 🪪 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---
 
## 👩‍💻 Author
**Kavitha Lingarajegowda**  
AI Product Management enthusiast passionate about building intelligent, human-centered systems.  
Exploring how LLMs and emerging AI tools can transform data understanding and decision-making.

