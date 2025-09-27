# SmartPDF-Chat-with-multiple-PDFs
Ask-Multiple-PDFs is an AI-powered Streamlit app that lets you upload one or more PDFs and chat with their content. It uses LangChain for retrieval-augmented generation, FAISS for fast semantic search, and Google Gemini for smart, contextual answers from your documents in real time.

Ask-Multiple-PDFs is an **AI-powered Streamlit application** that lets you upload one or more PDF documents and chat with their content in real time.  
It combines **LangChain** for retrieval-augmented generation (RAG), **FAISS** for fast semantic search, and **Google Gemini** for smart, contextual answers.

## ✨ Features
- 📂 Upload one or multiple PDF files.
- 💡 Ask natural-language questions and get context-aware answers directly from your documents.
- ⚡ Uses FAISS vector store for efficient semantic search.
- 🤖 Powered by Google Gemini via LangChain for intelligent responses.

## 🚀 Tech Stack
- **Python 3.10+**
- [Streamlit](https://streamlit.io/) – interactive web UI
- [LangChain](https://www.langchain.com/) – retrieval & chain management
- [FAISS](https://github.com/facebookresearch/faiss) – vector database
- Google Gemini API – LLM for answering queries

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Muskansingh111/SmartPDF-Chat-with-multiple-PDFs.git
   cd SmartPDF-Chat-with-multiple-PDFs
Create and activate a virtual environment (recommended)

bash
Copy code
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
Install dependencies

bash
Copy code
pip install -r requirements.txt
Set up environment variables

Create a file named .env in the project root and add:

ini
Copy code
GOOGLE_API_KEY=your_gemini_api_key
▶️ Usage
Run the Streamlit app:

bash
Copy code
streamlit run app.py


