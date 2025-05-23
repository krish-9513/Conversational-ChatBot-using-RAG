# 🧠 LangChain Document Chatbot with Streamlit

This project is a conversational AI application that lets users interact with documents through natural language. It is built using:

- [LangChain](https://www.langchain.com/)
- [Streamlit](https://streamlit.io/)
- [HuggingFace Embeddings](https://huggingface.co/)
- [FAISS](https://faiss.ai/)
- [Groq LLM](https://www.groq.com/)

## 🚀 Features

- 📄 Upload and parse PDF files
- 🔍 Generate embeddings using HuggingFace
- 🧠 Store/retrieve vectors using FAISS
- 💬 Answer questions with Groq-powered LLM
- 🖥️ Interactive chat UI via Streamlit

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
```

## ⚙️ Environment Variables

Create a `.env` file in the root directory with the following contents:

```env
HUGGINGFACE_API_KEY=your_huggingface_api_key
GROQ_API_KEY=your_groq_api_key
```

## 🏃 Run the App

Start the Streamlit application:

```bash
streamlit run app.py
```

## 📚 How It Works

1. 📄 Loads and splits PDF files into text chunks.
2. 🧬 Embeds the chunks using HuggingFace transformers.
3. 🗃️ Stores embeddings in FAISS for efficient similarity search.
4. 🔄 Uses LangChain to create a retrieval-augmented generation pipeline.
5. 💬 Presents an interactive chatbot with history through Streamlit.

## 🧰 Dependencies

Example `requirements.txt` content:

```txt
streamlit
langchain
langchain_community
langchain_core
langchain_groq
langchain_huggingface
faiss-cpu
python-dotenv
```

## 🪪 License

This project is licensed under the MIT License.

---

**Author**: [Your Name]  
**GitHub**: [yourusername](https://github.com/yourusername)
