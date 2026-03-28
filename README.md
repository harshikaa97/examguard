# 🎓 ExamGuard AI
AI-powered syllabus-aware exam paper generator using Retrieval-Augmented Generation (RAG).

## 🚀 Overview
ExamGuard AI generates structured, high-quality exam papers by combining:
- real question bank datasets
- syllabus PDF retrieval
- LLM-based question generation

Unlike basic generators, it ensures **context-aware, syllabus-aligned output**.

---

## ✨ Features
- 📚 Question generation from real datasets
- 🧠 RAG using LangChain + FAISS
- 🎯 Difficulty-based paper creation (Easy / Medium / Hard / Mixed)
- 📝 Structured exam paper format
- 🔁 Duplicate prevention logic
- 🌐 Streamlit-ready deployment

---

## 🧠 How It Works

```
User Input
   ↓
Dataset Filtering (difficulty/topic)
   ↓
Syllabus Retrieval (FAISS)
   ↓
LLM Generation
   ↓
Final Question Paper
```

---

## 🛠️ Tech Stack
- Python
- Pandas
- Streamlit
- LangChain
- FAISS
- PyPDF
- OpenAI / Gemini API

---

## 📂 Project Structure

```
examguard/
│── app.py
│── requirements.txt
│── README.md
│
├── data/
│   ├── syllabus_pdfs/
│   ├── vectorstore/
│   └── question_bank/
│
├── src/
│   ├── data_loader.py
│   ├── question_selector.py
│   ├── rag_pipeline.py
│   ├── prompt_builder.py
│   ├── validator.py
│   └── utils.py
│
└── notebooks/
    └── prototype.ipynb
```

---

## ⚙️ Installation

```bash
git clone https://github.com/harshikaa97/examguard.git
cd examguard
pip install -r requirements.txt
```

---

## ▶️ Run Locally

```bash
streamlit run app.py
```

---

## 🔐 Environment Variables

Create a `.env` file:

```
OPENAI_API_KEY=your_api_key
```

---

## 🌐 Deployment
Deploy easily using Streamlit Cloud by connecting your GitHub repository.

---

## 🚀 Future Improvements
- Answer key generation
- Bloom’s taxonomy tagging
- PDF export of question papers
- Multi-subject exam generation
- User authentication

---

## 👩‍💻 Author
Harshika Singh

---

## ⭐ If you like this project
Give it a star and feel free to contribute!