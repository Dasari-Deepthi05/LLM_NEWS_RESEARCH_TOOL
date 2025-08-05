# 📰 LLM News Research Tool

An AI-powered research assistant that extracts key insights from financial news articles using **LangChain**, **OpenAI**, and **Streamlit**. Designed for analysts, researchers, and professionals who want fast, source-based answers from news content.

---

## 🔍 Features

- 🔗 Input up to **3 financial news URLs**
- 💬 Ask questions about the articles using natural language
- 🧠 Get **LLM-generated summaries** and **contextual answers**
- 📚 View **source references** for every answer
- ⚡ Clean and interactive **Streamlit UI**

---

## ⚙️ Tech Stack

- **LangChain** – Manages LLM workflows and document chains  
- **OpenAI API** – Powers embeddings and question-answering  
- **FAISS** – Fast similarity search over embedded documents  
- **Streamlit** – Frontend web interface  
- **Python** – Core programming language  

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/news-research-tool.git
cd news-research-tool
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Up Environment Variables

Create a `.env` file in the root directory and add your OpenAI API key:

```
OPENAI_API_KEY=your-openai-api-key
```

### 4. Run the App

```bash
streamlit run app.py
```

---

## 📁 File Overview

| File/Folder            | Description                               |
|------------------------|-------------------------------------------|
| `app.py`               | Main Streamlit application file           |
| `.env`                 | Stores your OpenAI API key (not tracked)  |
| `requirements.txt`     | Required Python packages                  |
| `faiss_store_openai.pkl` | Local FAISS vectorstore (auto-generated) |

---

## 📌 Notes

- Only public news URLs are supported (paywalled sites may fail).
- Optimized for English-language financial news.
- Local FAISS store enables reusability without reprocessing.

---

## 🙌 Acknowledgments

- [LangChain](https://github.com/langchain-ai/langchain)  
- [OpenAI](https://openai.com/)  
- [Streamlit](https://streamlit.io/)
