 AI Resume & Interview Preparation System

 Project Overview
This project is an AI-powered Resume and Interview Preparation system designed to help students and job seekers improve their resumes and prepare for technical interviews.

The system analyzes a resume and a job description to identify missing skills, suggests resume improvements using AI, and conducts a mock interview with relevant questions.

---

 Features
- Resume text extraction from PDF
- Job description analysis
- Skill gap detection (missing skills)
- AI-based resume improvement suggestions
- Interview question generation
- Mock interview simulation

---

Technologies Used
- Python
- Natural Language Processing (NLP)
- OpenAI API
- Google Colab
- pdfplumber

---

 How to Run the Project

1. Open the notebook in **Google Colab**
2. Install required libraries
3. Upload your resume PDF file
4. Set your OpenAI API key as an environment variable
5. Run all cells sequentially

---
OpenAI API Key Setup
For security reasons, the OpenAI API key is **not included** in this repository.

Before running the notebook, add the following code in Google Colab:

```python
import os
os.environ["OPENAI_API_KEY"] = "your_api_key_here"
