# 📄✨ AI Résumé Analyser

An intelligent résumé analysis tool that evaluates resumes using machine learning and NLP techniques.  
This project extracts key information, analyses strengths, compares the résumé with job descriptions, and provides insights to help candidates improve their CVs.

---

## 🌟 Features

- 🔍 **Automated Résumé Parsing** – Extracts skills, experience, education, and keywords  
- 🧠 **AI-Based Skill & Keyword Matching**  
- 📊 **Score & Feedback Generation** – Rates the résumé based on industry standards  
- 📂 **Supports Multiple File Formats** (PDF, DOCX, TXT)  
- ⚙️ **NLP-powered Insights** using machine learning  
- 🎯 **Job Description Matcher** – Compares résumé with JD for compatibility  

---

## 🛠️ Tech Stack

### **Backend / AI**
- Python  
- NLTK / SpaCy  
- Scikit-Learn  
- TensorFlow / Keras (if using deep learning)  
- PyPDF2 / pdfplumber / docx2txt (for parsing)

### **Frontend (if included)**
- HTML  
- CSS  
- JavaScript  
- Flask / FastAPI backend

---

## 📂 Project Structure
```bash
AI-RESUME-ANALYSER/
│
├── app.py # Main backend application
├── parser.py # File extraction / parsing logic
├── analyser.py # AI/NLP analysis functions
├── model/ # ML model or vectorizer files
├── static/ # CSS, JS, Images (if web version)
├── templates/ # HTML templates for UI
│
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### **1️⃣ Clone the Repository**
```bash
git clone <YOUR_REPO_URL>
cd AI-RESUME-ANALYSER
```
2️⃣ Create a Virtual Environment
```
python -m venv venv
```
3️⃣ Activate the Virtual Environment

Windows
```
venv\Scripts\activate

```
Mac/Linux
```
source venv/bin/activate
```
4️⃣ Install Dependencies
```
pip install -r requirements.txt
```
5️⃣ Run the Application
```python app.py```


Your app will start at:

👉 http://127.0.0.1:5000

---

📤 Uploading a Résumé

Go to the homepage

Upload a PDF / DOCX / TXT file

View analysed output, score, missing keywords & recommendations


---


🧪 Retraining / Improving the Model

If your project uses ML classification:
```
python train.py
```

This will update vectorizers, models, and keyword mappings.

---

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repository and submit improvements.

---

👩‍💻 Author

Designed & Developed by Preethi S
Feel free to star ⭐ the repo if you like it!
