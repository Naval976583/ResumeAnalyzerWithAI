# AI Resume Critiquer

An AI-powered resume analysis tool built with Streamlit and OpenAI.  
Upload your resume (PDF or TXT) and receive structured, constructive feedback tailored to your target job role.

---

## 🚀 Features

- 📄 Upload resumes in PDF or TXT format  
- 🎯 Optional job role targeting for personalized feedback  
- 🧠 AI-generated structured feedback including:
  - Content clarity and impact
  - Skills presentation
  - Experience descriptions
  - Role-specific improvement suggestions
- ⚡ Clean and simple Streamlit interface  

---

🧠 How It Works
1. User uploads a resume (PDF or TXT).

2. The app extracts text using PyPDF2 (for PDFs) or direct decoding (for TXT).

3. A structured prompt is generated.

4. The OpenAI model (gpt-4o-mini) analyzes the resume.

5. Feedback is displayed in a structured format within the app.



## 🛠️ Tech Stack

- Streamlit – Web app framework  
- PyPDF2 – PDF text extraction  
- OpenAI Python SDK – AI model integration  
- python-dotenv – Environment variable management  

---


---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Naval976583/ResumeAnalyzerWithAI.git
cd ResumeAnalyzerWithAI
```
2️⃣ Create a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```
3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
🔑 Environment Variables
Create a .env file in the root directory and add your OpenAI API key:
```bash
OPEN_API_KEY=your_openai_api_key_here
```
▶️ Running the Application
```bash
streamlit run app.py
```
The app will open in your browser at:
```bash
http://localhost:8501
```


📌 Example Use Cases

* Students preparing for internships

* Professionals switching careers

* Applicants targeting specific job roles

* Anyone wanting structured resume improvement feedback


🚧 Future Improvements

* ATS score simulation

* Keyword matching vs job description

* Downloadable feedback report (PDF)

* Support for DOCX files

* Resume scoring system

* Authentication for multi-user deployment
