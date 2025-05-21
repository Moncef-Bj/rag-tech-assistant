# 📚 RAG Tech Assistant

This project is a prototype of a **Retrieval-Augmented Generation (RAG)** system that answers questions using technical documentation such as manuals, internal guides, or Markdown files.

The system combines:

- **Document indexing and embedding** (via FAISS or Chroma)
- **Context-aware question answering** using a Large Language Model (LLM)

---

## 🎯 Objective

Enable users (e.g. employees, operators, engineers) to ask natural language questions and receive relevant, accurate answers **grounded in their actual documentation**.

Example use cases:
```
- Internal IT support
- Technical process documentation
- Supply chain SOP manuals
- Product catalogs and support guides
```
---

## ⚙️ How It Works
```
1. 📥 Upload or load PDF / Markdown / TXT documents
2. 🔎 Documents are chunked and embedded into a vector database
3. 🧠 The user submits a question via CLI or simple UI
4. 📌 Top relevant chunks are retrieved and sent to the LLM
5. 💬 The LLM responds using both the question and the retrieved context
```
---

## 🧪 Example (Coming soon)

**Question:**  
> How do I restart the RFID scanning module if it crashes?

**Answer:**  
> According to section 4.3 of the SOP manual, you should press the reset switch on the control panel and hold it for 5 seconds...

---
🛠️ **Project status:**  
This is the initial setup — only the README file is available for now. The development of the assistant prototype will begin shortly.

## 🚀 Planned Features
```
- PDF, Markdown and TXT support
- Embedding with OpenAI or local models (e.g., `Instructor`, `MiniLM`)
- Vector search via FAISS or Chroma
- Optional Streamlit-based user interface
- Support for Mistral or GPT for response generation
- Citation of document sources in responses
```
---

## 🤝 Contributions

Ideas, improvements and feedback are welcome!  
Feel free to open issues or pull requests to:
```
- Support new document formats
- Improve chunking strategies
- Add multilingual support
- Optimize retrieval pipelines
```
---

## 📄 License

MIT License

