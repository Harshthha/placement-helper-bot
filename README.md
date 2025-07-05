# 🎓 AI Placement Helper Bot

An intelligent, AI-powered chatbot designed to assist students with resume tailoring, job matching, aptitude prep, and career guidance. Built using **Google Gemini API**, **Streamlit**, and **Firebase**, this tool offers personalized support to students preparing for placements and internships.

## 🚀 Features

- ✅ Resume vs Job Description Comparator  
- ✉️ Cover Letter Generator  
- 📊 ATS Optimization Tips  
- 📅 Placement Calendar (Coming Soon)  
- 🧠 Aptitude Prep Generator (Coming Soon)  
- 🗣️ Voice Input & Output (Planned)  
- 📎 PDF/Text Upload  
- 🔐 User Authentication via Firebase  

## 🛠️ Tech Stack

- **Frontend:** Streamlit  
- **AI Engine:** Google Gemini API  
- **Auth & Database:** Firebase Auth + Firestore (Firebase Admin SDK)  
- **OCR (Planned):** pdfplumber 
- **Deployment:** Render

## 📂 Folder Structure

<pre>
ai_chatbot/
├── .venv/                    # Virtual environment
├── src/
│   ├── main.py               # Streamlit entry point
│   ├── utils/
│   │   └── firebase.py       # Firebase admin setup
│   │   └── gemini.py         # Gemini interaction functions
│   │   └── parser.py         # Resume/Job parsing utils
├── requirements.txt
├── README.md
└── .env                      # Environment variables (not committed)
</pre>

## 🧪 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/ai-placement-helper.git
   cd ai-placement-helper

2. Create and Activate Virtual Environment
   ```bash
      python3 -m venv .venv  
      source .venv/bin/activate
3. Install Dependencies
    ```bash
    pip install -r requirements.txt
4. Add Environment Variables
   Create a .env file in the root:
   ```bash
      GOOGLE_APPLICATION_CREDENTIALS_JSON=<your Firebase JSON string>
      GEMINI_API_KEY=<your Gemini API Key>
5.	Run the App
   ```bash
      streamlit run src/main.py
   
   
   
