# 📄 Document Search Engine App

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Retrieval_Augmented_Generation-0A66C2?style=for-the-badge)

**A powerful Streamlit-powered RAG (Retrieval-Augmented Generation) application** that allows you to upload documents and ask natural language questions. It intelligently retrieves relevant information and generates accurate, context-aware answers using embeddings and LLMs.

Built as part of the **RAG-Mastery** learning journey — covering everything from basic chunking & retrieval to advanced RAG concepts.

---

## ✨ Features

- **Semantic Document Search** — Upload PDFs, TXT, or other documents and get intelligent answers
- **End-to-End RAG Pipeline** — Document loading, chunking, embedding generation, vector storage & retrieval
- **LLM Integration** — Powered by OpenAI (easily extendable to other models)
- **Clean & Interactive UI** — Built with Streamlit for a smooth user experience
- **Modular Codebase** — Well-organized `src/` structure for easy learning and extension
- **Great for Experimentation** — Perfect foundation to try advanced RAG techniques, agents, LangGraph, etc.

---

## 🚀 Live Demo

**Deployed Application**: [Document Search Engine App](https://document-search-engine-app.streamlit.app/)


**Demo Video**:

https://github.com/mani24singh/Document-Search-Engine-App/blob/main/assets/output_demo.mp4

---

## 🛠️ Tech Stack

- **Language**: Python 3.11+
- **UI Framework**: Streamlit
- **RAG Framework**: LangChain
- **Embeddings**: OpenAI Embeddings
- **LLM**: OpenAI GPT models
- **Package Manager**: uv (recommended)

---

## 📥 How to Clone and Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/mani24singh/Document-Search-Engine-App.git
cd Document-Search-Engine-App
```

### 2. Create Virtual Environment (Recommended)

```bash
# Install uv (fast Python package manager)
pip install uv

# Create and activate virtual environment
uv venv --python 3.11

# Activate environment
# Windows:
.venv\Scripts\activate
# macOS / Linux:
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
uv pip install -r requirements.txt
```

### 4. Add Your OpenAI API Key

Create a `.env` file in the root directory and add your key:

```env
OPENAI_API_KEY=sk-your-openai-api-key-here
```

> **Note**: `.env` is already added to `.gitignore` for security.

### 5. Run the Application

```bash
streamlit run streamlit_app.py
```

The app will automatically open in your browser.

---

## 📁 Project Structure

```
Document-Search-Engine-App/
├── assets/                  # Demo videos and images
├── data/                    # Sample documents
├── src/                     # Core RAG logic and modules
├── .env.example             # Example environment variables
├── .gitignore
├── LICENSE
├── main.py                  # Alternative entry point
├── requirements.txt
├── README.md
└── streamlit_app.py         # Main Streamlit application
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to fork the repository and submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## ⭐ Show Your Support

If you liked this project or found it helpful for learning RAG, please give it a ⭐ on GitHub!  
It really helps the project reach more people.

---

**Made with ❤️ for learning and building better RAG systems.**
