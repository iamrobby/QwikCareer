# 🚀 QwikCareer  
### *AI-Powered Job Search, Ranking & Personalized Recommendations*

QwikCareer is an intelligent multi-agent system that automates job searching, job ranking, profile-matching, and daily email delivery.  
It integrates **Gemini-2.5**, **SerpAPI**, and a custom pipeline of AI agents to provide fast and personalized job recommendations.

---

## 🔥 Features

### 🟡 **1. AI Recruiter System (Multi-Agent Architecture)**  
QwikCareer uses 3 specialized agents:

#### **🔍 Search Agent**
- Uses **SerpAPI Google Jobs API**  
- Fetches job postings (title, company, location, full application link)

#### **📊 Analysis Agent**
- Evaluates each job against the user profile  
- Logs each job using a custom logging tool  
- Scores match (1–10)

#### **🎯 Recruiter Agent**
- Synthesizes results  
- Produces final recommendation report  
- Highlights top matches  
- Ensures **full application links** are included

---

### ✉️ **2. Automatic Email Delivery**
Sends the final job report to your email using:
- Gmail SMTP  
- App Passwords (secure authentication)

---

### ⚙️ **3. Custom Tools**
- `serp_job_search_tool()` — Live job search using SerpAPI  
- `log_job_to_db()` — Logs each job in a simulated DB  
- Email sending function  
- Multi-step agent execution using Gemini tools

---

## 🧩 How It Works


---

## 🔑 Required Secrets (Colab / Kaggle)

Store the following keys in your notebook environment:

| Secret Name | Description |
|-------------|-------------|
| `GOOGLE_API_KEY` | Gemini 2.5 API key |
| `SERPAPI_API_KEY` | Key for SerpAPI Google Jobs |
| `MY_EMAIL` | Your Gmail address |
| `MY_EMAIL_APP_PASSWORD` | Gmail App Password |

---

## 📚 Tech Stack

- **Python 3.10+**
- **Gemini 2.5 API (google-genai)**
- **SerpAPI**
- **Requests**
- **SMTP email service**
- **Custom multi-agent architecture**

---

## ▶️ Running the Notebook

1. Upload your notebook to Google Colab  
2. Add secrets in the *Colab User Data* panel  
3. Run all cells  
4. Receive your job report in email  

---

## 📁 Project Intent

This project is intended to evolve into an AI job-search platform that:
- understands your profile  
- fetches real-time job listings  
- ranks and sorts them  
- delivers actionable job recommendations instantly  

Future version may include:
- A web UI (Next.js or Streamlit)  
- User profile memory  
- Multi-day job tracking  
- Auto-apply functionality  

---

## 🤝 Contributing

Feel free to open issues or feature requests.  
Pull requests are always welcome!

---

## 📜 License

MIT License – free for personal & commercial use.

