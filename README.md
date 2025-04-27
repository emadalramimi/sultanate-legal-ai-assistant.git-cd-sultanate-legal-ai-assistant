# 📜 Sultanate Legal AI Assistant - README

Welcome to the **Sultanate Legal AI Assistant** challenge!  
This project is designed to build an AI-powered chatbot that can search, summarize, compare, and generate documents and images based on official Omani laws.

---

## 🫩 Project Overview

The goal of this project is to:
- Create an intelligent chatbot that interacts with a corpus of legal documents.
- Answer user queries based on the documents.
- Summarize articles or sections from specific laws.
- Compare laws between different legal documents.
- Accept voice-based queries and reply accordingly.
- Dynamically generate legal documents (PDF) and associated images.
- Return downloadable files to users.

---

## 🗂️ Project Structure

```plaintext
/ (root)
│
├── app/
│   ├── main.py         # Main backend logic
│   ├── chatbot.py      # Chatbot interaction logic
│   ├── document_loader.py # Document parsing and embedding
│   ├── voice_module.py # Voice input/output handling
│   ├── generator.py    # Document and image generation
│   ├── utils.py        # Helper functions
│   └── templates/
│       ├── contract_template.docx
│       └── certificate_template.png
│
├── data/
│   └── documents/      # Legal documents (PDFs)
│
├── models/
│   └── embeddings/     # Saved embeddings for search
│
├── frontend/
│   ├── app.py          # Streamlit or Gradio app
│   ├── assets/         # Images, styles
│
├── README.md           # (this file)
└── requirements.txt    # Python libraries needed
```

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/emadalramimi/sultanate-legal-ai-assistant.git
cd sultanate-legal-ai-assistant
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Set environment variables (if needed):
- Example: OpenAI API keys, etc.

---

## 🚀 How to Run

### 1. Start Backend

```bash
python app/main.py
```

### 2. (Optional) Start Frontend

```bash
streamlit run frontend/app.py
```

---

## 📚 Features by Level

| Level | Feature | Status |
|:------|:--------|:-------|
| 1 | Smart Search Bot (Document QA) | 🔲 |
| 2 | Section Navigation + Summarization | 🔲 |
| 3 | Cross-Document Comparison + Voice Interaction | 🔲 |
| 4 | Document + Image Generation | 🔲 |
| 5 | AI Reports and Case Study Creation | 🔲 |

👉 ✅ = Completed | 👉 🔲 = In Progress

---

## 🧐 Technologies Used

- **Python 3.10+**
- **OpenAI GPT-4** (or local LLMs)
- **LangChain** / **LlamaIndex**
- **FAISS / ChromaDB** for document embeddings
- **PyMuPDF / pdfplumber** for parsing PDFs
- **WeasyPrint / ReportLab** for PDF generation
- **Pillow** for Image generation
- **Streamlit / Gradio** for frontend
- **Whisper / Vosk** for voice input
- **gTTS / pyttsx3** for voice output (optional)

---

## 🧪 Testing

- Unit tests are recommended (pytest or unittest).
- Example test cases:
  - Search query returns correct paragraph.
  - Section extraction works for a specific article.
  - Generated PDF matches the conversation input.
  - Voice input is correctly transcribed.

---

## 💬 Usage Example

**Text Query:**

> "Summarize Article 15 from قانون العمل."

**Voice Query:**

🎤 (User speaks)  
_"Compare penalties for cybercrime and drug crime in Oman."_

---

## 📦 Output

- 🌟 Dynamic legal document (.pdf)
- 🌟 Certificate-style dynamic image (.png or .jpg)
- 🌟 Download link provided to the user

---

## 📝 Guidelines

- Write clean, documented code.
- Push updates regularly.
- Follow modular architecture for easier integration.
- Each feature must be tested with different document samples.

---

## 🏆 Bonus Points

- Arabic language support (preferably).
- User login and session management.
- Advanced template customization.
- Deployment to cloud (Azure, AWS, etc.).

---

## 🙇️ Acknowledgements

Thanks to the Sultanate's official legal repositories and open-source contributors whose tools are used to make this project possible.

---

# 🗓️ Timeline

| Deadline | Deliverable |
|:---------|:------------|
| +4 days | Level 1 Completed |
| +5 days | Level 2 Completed |
| +6 days | Level 3 Completed (with Voice Chat) |
| +6 days | Level 4 Completed (Document + Image) |
| +7 days | Level 5 Completed (AI Reports) |

---

# 📩 Contact

For any questions or clarifications, please contact:  
**Challenge Supervisor:** Emad Al-Ramimi  
**Email:** ai@ankaa.om

---

# ⚡ Let's Build the Future of Legal AI!
