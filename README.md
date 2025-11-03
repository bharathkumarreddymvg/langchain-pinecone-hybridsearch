# 🧠 LangChain + Pinecone Hybrid Search Agent

An intelligent **hybrid semantic search system** built with **LangChain**, **Pinecone**, and **Groq**.  
It combines **dense embeddings** and **sparse keyword search** to deliver accurate and context-aware information retrieval.

---

## 🚀 Overview

This project demonstrates how to use **LangChain retrievers** with **Pinecone vector storage** to perform hybrid search — a blend of semantic and lexical matching — ideal for document retrieval, chatbots, and enterprise knowledge systems.

Key Features:
- 🔎 **Hybrid Search** — combines dense + sparse retrieval for optimal relevance  
- 🧩 **LangChain Integration** — unified interface for embeddings, retrievers, and LLMs  
- ⚙️ **Pinecone Vector Database** — scalable, high-speed vector indexing  
- ⚡ **Groq / OpenAI Models** — used for language understanding and summarization  
- 💬 Ready for chatbot or document Q&A workflows  

---

## 🧰 Tech Stack

| Layer | Tools Used |
|-------|-------------|
| **Framework** | LangChain |
| **Vector DB** | Pinecone |
| **LLMs** | Groq / OpenAI |
| **Embeddings** | HuggingFace Sentence Transformers |
| **Frontend (optional)** | Streamlit |
| **Utilities** | dotenv, pandas, bs4, pytube, playwright |

---

## 🧩 Project Structure

```

langchain-pinecone-hybridsearch/
│
├── app.py                     # main app / pipeline
├── requirements.txt            # dependencies
├── .env                        # API keys (excluded via .gitignore)
├── notebooks/                  # optional notebooks for experiments
├── utils/                      # helper scripts
└── README.md

````

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/langchain-pinecone-hybridsearch.git
cd langchain-pinecone-hybridsearch
````

### 2️⃣ Create virtual environment

```bash
python -m venv venv
source venv/bin/activate    # (Mac/Linux)
venv\Scripts\activate       # (Windows)
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔐 Environment Setup

Create a `.env` file in the project root and add your keys:

```
PINECONE_API_KEY=your_pinecone_api_key
GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
```

*(Make sure `.env` is listed in `.gitignore` before pushing to GitHub.)*



---

## 🧩 Optional: Streamlit UI

If your project includes a Streamlit app:

```bash
streamlit run app.py
```

Then open [http://localhost:8501](http://localhost:8501) in your browser.

---

## 🌐 Deployment

You can deploy this project on:

* **Streamlit Cloud** — easiest (supports `.env` secrets)
* **Google Cloud / Docker + Kubernetes**
* **Render / Railway / HuggingFace Spaces**

Example for Streamlit:

```bash
pip install streamlit
streamlit run app.py
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch (`feature/your-feature`)
3. Commit changes and push
4. Open a Pull Request

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Bharath Kumar Reddy**
📍 Data Science & AI Enthusiast
🔗 [LinkedIn](https://www.linkedin.com/in/bharathkumarreddymvg/)

``
