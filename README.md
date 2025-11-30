
# Chatbot-RAG — Retrieval-Augmented Generation with PostgreSQL + Ollama

![Python-3](https://github.com/user-attachments/assets/5ffb70e5-f7c3-4678-9142-1d2d16253d89)
![PostgreSQL-pgvector-blue](https://github.com/user-attachments/assets/7e1b2a46-891d-427a-922a-1e890ba4729c)
![LLM-Ollama-green](https://github.com/user-attachments/assets/c50ab774-f715-4600-bb82-1cef0954b818)
![Status-Working-success](https://github.com/user-attachments/assets/d1c3ac96-5f5c-40f0-b660-3e42636d088e)

A **RAG chatbot** that searches your local documents in PostgreSQL using **pgvector** and generates answers with a local **Ollama LLM**. Lightweight, private, and easy to run.


---

## 📚 Dataset

Download `.txt` files here:  
[Corpus Link](https://www.info.univ-tours.fr/~antoine/parole_publique/Accueil_UBS/index.html)  

Place them in:  

```

data/

````

---

## ⚙️ Requirements

- Python 3.10+
- PostgreSQL 15+ with **pgvector**
- Ollama installed (e.g., `gemma2:2b` model)

---


## 🚀 Features

* Retrieval-Augmented Generation (RAG)
* Vector similarity search in PostgreSQL
* Local LLM via Ollama
* CLI chatbot interface
* Easy to extend (API, web interface, Docker, etc.)


