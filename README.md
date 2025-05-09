# FAISS Document Retriever

A simple and extensible local document retriever using FAISS and SentenceTransformers. Supports `.txt`, `.md`, and `.pdf` files.

---

## 🚀 Features

- Chunking and vector indexing of documents
- Natural language query over local files
- Save/load FAISS index
- Supports `.txt`, `.md`, `.pdf`

---

## 🛠 Installation

```bash
git clone https://github.com/yourusername/homework_week3_retriever.git
cd homework_week3_retriever

# (Optional) Create a virtual environment
python -m venv homework_w3_retriever

# Activate the virtual environment
# On macOS/Linux:
source homework_w3_retriever/bin/activate
# On Windows:
homework_w3_retriever\Scripts\activate

# Install dependencies
pip install -r requirements.txt