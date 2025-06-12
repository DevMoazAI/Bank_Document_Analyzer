# 🏦 Bank Document Analyzer

![Banner](Bank_document_analyzer.png)

> 🔍 Upload banking, loan, or insurance documents (PDF/image) and get an instant AI-generated explanation in simple terms. Red flags? We’ll highlight them too.

---

## 🚀 Features

- 📷 Upload **images or PDFs**
- 🧠 **OCR** extracts text from scans
- 🌐 **Translation** (e.g., Urdu to English)
- 💬 **LLM summaries** powered by Groq API
- 🚩 Flags risky or hidden terms
- 📎 Supports **multiple files at once**

---

## 💡 How It Works

1. 📤 Upload document(s)
2. 🔍 OCR extracts the text
3. 🌐 Text translated to English (if needed)
4. 🤖 Groq LLM summarizes and explains the content
5. 📄 Output shown in an easy-to-understand format

---

## 🛠️ Setup Instructions

```bash
# 1. Clone the repo
git clone https://github.com/DevMoazAI/Bank_Document_Analyzer.git

cd Bank-document-analyzer

# 2. Create and activate virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Create .env file and add your API key
