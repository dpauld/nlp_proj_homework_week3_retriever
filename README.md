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
**Step 1**: download the code in your device.
```bash
git clone https://github.com/yourusername/nlp_proj_homework_week3_retriever.git
cd nlp_proj_homework_week3_retriever
```

(Optional) Step 2: Create a virtual environment
```bash
python -m venv nlp_proj_hw_w3
```

Activate the virtual environment
```bash
    # On macOS/Linux:
    source nlp_proj_hw_w3/bin/activate
    # On Windows:
    nlp_proj_hw_w3\Scripts\activate
```

**Step 3**: Install dependencies
```bash
pip install -r requirements.txt
```