# 🤖 AI Resume Screening & Matching Agent

This project is an AI-powered resume screener that automatically extracts text from PDF resumes, compares each to a given job description, and ranks them based on semantic similarity using transformer-based language models.

---

## 📌 Problem Statement

Recruiters often spend hours manually reviewing resumes, which can be slow, inconsistent, and biased. This AI agent automates the screening process by using natural language processing (NLP) techniques to assess and rank resumes based on how well they match a job description.

---

## 🚀 Features

- 📄 Extracts text from PDF resumes using `pdfplumber`
- 💡 Converts resume and job description into semantic vectors using `sentence-transformers`
- 📈 Ranks resumes by similarity using cosine similarity
- 📊 Visualizes ranking scores with `matplotlib`
- 📥 Exports results to Excel and provides easy download in Colab
- ✅ Works entirely in Google Colab — no deployment needed

---

## 🛠️ Tools and Libraries Used

| Tool/Library           | Purpose |
|------------------------|---------|
| `pdfplumber`           | Extract text from resumes (PDFs) |
| `sentence-transformers`| Generate embeddings |
| `scikit-learn`         | Cosine similarity scoring |
| `pandas` / `numpy`     | Data processing |
| `matplotlib`           | Score visualization |
| `openpyxl`             | Export results to Excel |
| `google.colab.files`   | Upload and download support in Colab |

---

## 🧠 How It Works

1. **Upload Resumes** (PDF format) into Google Colab.
2. **Provide a Job Description** as input text.
3. The script extracts resume content and converts all text into embeddings.
4. Uses **cosine similarity** to score how closely each resume matches the job.
5. Sorts resumes and generates:
    - 📊 A bar chart of top matches
    - 📁 An Excel file with scores
6. Download the results or modify it for more advanced screening.

---

## 📂 Files Included

- `AI_Resume_Screener.ipynb` – Main Colab notebook
- `AI_Resume_Screener_Report.pdf` – Project report (problem, tools, working)
- `requirements.txt` – All required libraries
- `resume_match_results.xlsx` – Output of ranked resumes (auto-generated)

---

## 💡 Future Improvements

- Add OCR for scanned resume PDFs
- Include skill-based keyword scoring
- Integrate with a web interface or HR API
- Support for multiple job roles in batch mode

---

## 📬 Contact

For queries, suggestions, or collaboration ideas, feel free to connect via GitHub or [LinkedIn](https://www.linkedin.com/).

---

> **Built with Python, NLP, and a mission to simplify hiring.**
