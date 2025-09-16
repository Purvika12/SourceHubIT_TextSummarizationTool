# 📝 AI Text Summarization Tool

## 📌 Objective
This project builds an **AI-powered summarization tool** in Python that automatically shortens long text (articles, blogs, reports, or documents) into clear and concise summaries of **3–5 sentences**.  
The goal is to help users save time by quickly understanding the key points without reading the entire content.

---

## 🛠️ Tech Stack
- **Python 3**
- **Google Colab / VS Code**
- **Libraries:**
  - [HuggingFace Transformers](https://huggingface.co/transformers/)
  - Torch
  - NLTK (optional for preprocessing)

---

## ⚙️ Installation & Setup

### 🔹 Option 1: Run on Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/)  
2. Upload the notebook: `summarization_tool.ipynb`  
3. Run each cell step by step  
4. Upload a `.txt` file or enter text manually to summarize  

### 🔹 Option 2: Run Locally (VS Code / Jupyter Notebook)
```bash
# Create virtual environment (optional)
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux

# Install dependencies
pip install nltk transformers torch
