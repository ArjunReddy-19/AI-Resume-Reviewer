# ResumeMind – AI-Powered Role Recommendation Tool

ResumeMind is a modern **AI-driven web application** that analyzes resumes (PDF) and recommends suitable job roles based on skills, experiences, and keywords.  
It leverages **Google Gemini AI** (and optionally OpenAI GPT) for semantic analysis, providing users with accurate and insightful career guidance.

---
## 🔑 Core Tech Badges

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) 
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) 
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?logo=google&logoColor=white)
![OpenAI GPT](https://img.shields.io/badge/OpenAI-GPT-412991?logo=openai&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-102230?logo=scikitlearn&logoColor=orange)
![dotenv](https://img.shields.io/badge/dotenv-ECB22E?logo=dotenv&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Streamlit Cloud](https://img.shields.io/badge/Streamlit%20Cloud-FF4B4B?logo=streamlit&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)

---
## 🚀 Key Features
- 📂 **Drag & Drop Resume Upload** – Simple and user-friendly interface.  
- 🤖 **AI-Powered Role Recommendations** – Matches your skills with relevant job roles.  
- 🎯 **Skill Extraction & Insights** – Identifies both explicit and hidden skills.  
- 💬 **Actionable Resume Feedback** – Helps improve resume quality.  
- 🎨 **Clean, Modern UI** – Built with Streamlit for a seamless experience.  

---

## 🛠️ Tech Stack
- **Frontend/UI**: Streamlit  
- **Backend**: Python  
- **AI/ML Models**: Google Gemini API (optional OpenAI GPT)  
- **PDF Parsing**: PyPDF2  
- **Environment Management**: Python-dotenv  
- **Deployment**: Streamlit Cloud / Docker / Vercel / Render  

---

## 📂 Project Structure

resumemind

│── app.py              
│── requirements.txt   
│── .env.example      
│── README.md           
│── assets          


---

## ⚙️ Installation & Setup 🛠️

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/resumemind.git
cd resumemind
````

### 2. Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Keys

Create a `.env` file in the project root:

```ini
GEMINI_API_KEY=your_gemini_api_key_here
OPENAI_API_KEY=your_openai_api_key_here  # Optional
```

### 5. Run the Application

```bash
streamlit run app.py
```

Open [http://localhost:8501](http://localhost:8501) in your browser.

---
## 🧪 Example Output

**Input:** Software Engineer Resume (PDF)

**Output:**

* Recommended Roles: Data Scientist, Python Developer, Machine Learning Engineer
* Key Skills: Python, SQL, Machine Learning, Data Visualization
* Feedback: "Add quantifiable achievements to highlight impact."

---

## 🌍 Deployment Options

* **Streamlit Cloud** → Fastest way to go live.
* **Docker** → For containerized deployments.
* **Vercel / Render** → Scalable hosting platforms.
* **Heroku** → Legacy-friendly option.

---

## 🛤️ Roadmap

* 🌏 Multilingual Resume Support
* 🔗 LinkedIn Integration
* 📊 Job Market Insights & Trend Analysis
* 🏢 HR Dashboard for bulk resume screening

---

## 🔐 Security

* Resumes are **not stored permanently**.
* API keys are managed securely using `.env` files.
* Fully compliant with data privacy practices.

---

## 📜 License

This project is licensed under the **MIT License** – free to use, modify, and distribute.

---

## 🙌 Acknowledgements

* **Google Gemini AI** for semantic intelligence.
* **Streamlit** for an elegant frontend.
* **Python Open Source Community** for powerful libraries.







