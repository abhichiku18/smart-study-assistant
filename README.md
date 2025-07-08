# 📚 Smart Study Assistant – AI-Powered Q&A Chatbot

An interactive AI chatbot that lets you **upload any PDF document and ask natural language questions** about its content.  
Built using **Gradio**, **FAISS**, **sentence-transformers**, and **transformers** – works fully offline once models are downloaded.

> 🧪 Ideal for students, researchers, and anyone who wants to explore large documents quickly.

---

## ✨ **Features**

✅ Upload and process PDF documents (100+ pages)  
✅ Semantic search using dense embeddings & FAISS vector index  
✅ Ask any question – get instant, context-aware answers  
✅ Lightweight and fast – sub-1 second query latency  
✅ Simple, clean Gradio interface  
✅ Fully runs inside Google Colab – no API keys or backend required

---

## ⚙️ **Tech Stack**

- Python
- [sentence-transformers](https://www.sbert.net/) (`all-MiniLM-L6-v2`)
- [transformers](https://huggingface.co/transformers/) (DistilBERT QA pipeline)
- FAISS for vector search
- PyMuPDF for PDF text extraction
- Gradio for frontend interface

---

## 🚀 **How to run (in Colab)**

1. Open the notebook in Google Colab  
2. Run cells in order:
   - Install libraries
   - Load models
   - Define helper functions
   - Launch Gradio app
3. Upload your PDF and start asking questions!

#ScreenShot
![AI- chatbot screenshot](https://github.com/user-attachments/assets/8666fe73-7f69-40c3-8afb-545b20e82bb5)

