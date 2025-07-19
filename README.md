# Resume-checkers

# 🚀 Resume Analyzer Based on Job Description (JD)

An intelligent resume checker that uses OCR, NLP, and ATS-based role matching to analyze your resume against a job description. Built with **Python**, **Gradio**, and **PyMuPDF**, this tool provides a visual ATS score and personalized role recommendations to improve your chances of landing the job.

---

## 🔍 Features

- 📄 OCR-based Resume Parsing (PDF/Image)
- 🧠 Keyword Extraction from Job Descriptions
- 🎯 Skill Matching with 10+ Predefined Job Roles
- 📊 ATS Match Score with Pie Chart Visualization
- 💡 Personalized Suggestions for Improvement
- ⚡️ Instant Web App Interface using Gradio

---

## 👨‍💻 Supported Roles

- AI/ML Intern  
- Data Analyst  
- Web Developer  
- Backend Developer  
- Full Stack Developer  
- Cloud Engineer  
- DevOps Engineer  
- Cybersecurity Analyst  
- Business Analyst  
- Data Scientist  

---

## 🛠 Tech Stack

- `Python`
- `Gradio` (Frontend)
- `pytesseract` (OCR)
- `nltk` (NLP)
- `PyMuPDF`, `pdf2image` (PDF Parsing)
- `matplotlib` (Visualization)

---

## 🚦 How It Works

1. Upload your **resume** (PDF/Image format).
2. Paste the **job description**.
3. Get:
   - ✅ **ATS Match Score**
   - 💼 Best Fit Roles
   - 💡 Suggestions to Improve

---

## 📦 Setup Instructions

```bash
# Install dependencies
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install poppler-utils

# NLTK Downloads
python3
>>> import nltk
>>> nltk.download("punkt")
>>> nltk.download("stopwords")
>>> exit()

# Run the app
python resume_checker.py
