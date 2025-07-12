````markdown
# 🔍 ChatGroq RAG Chatbot

A **Retrieval-Augmented Generation (RAG)** web application powered by **Streamlit**, **LangChain**, **Groq's LLMs**, and **FAISS**, designed to allow real-time question answering from custom document sources or live websites.

Built by **Ankit Porwal**.

---

## 🚀 Features

- 🔗 Loads content directly from a live web page
- 📚 Splits and embeds content using open-source **Ollama embeddings**
- 🧠 Stores vectorized content using **FAISS**
- ⚡ Uses **Groq's ultra-fast LLMs (like LLaMA 3)** for answering queries
- 🖥️ Simple and interactive **Streamlit UI**
- 🔍 Shows document chunks used in answering the question (document similarity search)

---

## 🛠️ Tech Stack

| Tool           | Purpose                            |
|----------------|------------------------------------|
| Streamlit      | Frontend Web App UI                |
| LangChain      | RAG chaining and document handling |
| Groq API       | LLM inference                      |
| Ollama         | Open-source embeddings             |
| FAISS          | Vector store for similarity search |
| WebBaseLoader  | Loads data from websites           |
| Python         | Core language                      |

---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/chatgroq-rag.git
cd chatgroq-rag
````

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Set up environment variables:**

Create a `.env` file and add your API key:

```env
GROQ_API_KEY=your_groq_api_key
```

4. **Run the Streamlit app:**

```bash
streamlit run app.py
```

---

## 📄 Project Structure

```
chatgroq-rag/
│
├── app.py                  # Main Streamlit app
├── requirements.txt        # Python dependencies
├── .env                    # API key storage
└── README.md               # Project documentation
```

---

## 📸 Preview

<img width="1919" height="616" alt="Screenshot 2025-07-12 223830" src="https://github.com/user-attachments/assets/98823251-4e75-44b6-b075-6477652f0b73" />

---

## 🧠 How It Works

1. Loads content from a provided web page (e.g., a LangChain or ML article).
2. Splits the text into chunks and creates embeddings using `OllamaEmbeddings`.
3. Stores those embeddings in a local FAISS vector store.
4. User submits a question through the Streamlit interface.
5. LangChain’s retrieval chain fetches the most relevant chunks.
6. The selected LLM (via Groq API) answers based on the retrieved context.

---

## 📬 Contact

Feel free to connect:

* 💼 [LinkedIn – Ankit Porwal](https://www.linkedin.com/in/ankitporwal04)
* 📧 [ankit.email@example.com](mailto:ankitporwal4403@gmail.com)

---

## 🪪 License

This project is open-source and available under the [MIT License](LICENSE).

```

---

Let me know if you'd like to customize this further for:
- GitHub topics and tags
- PDF document ingestion (if you're using it later)
- Deployment (e.g., Streamlit Cloud or Hugging Face Spaces)

Just drop me a note!
```
