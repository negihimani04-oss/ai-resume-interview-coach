<div align="center">
  <img src="https://img.shields.io/badge/AI-Google%20Gemini-blue?logo=googlecloud&logoColor=white" alt="Google Gemini">
  <img src="https://img.shields.io/badge/Deployment-Vercel-black?logo=vercel&logoColor=white" alt="Vercel">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
</div>

<br/>

<h1 align="center">🤖 AI Resume Coach</h1>
<p align="center">
  <strong>Stop writing resumes. Start tailoring them.</strong><br />
  An intelligent web application that uses Google's Gemini AI to analyze and tailor your resume to specific job descriptions in seconds.
</p>

<p align="center">
  <a href="https://your-vercel-url.vercel.app/">🌐 Live Demo</a> •
  <a href="#-features">✨ Features</a> •
  <a href="#-tech-stack">🛠️ Tech Stack</a> •
  <a href="#-getting-started">🚀 Getting Started</a>
</p>

---

## 📌 Overview

Applying for jobs is tedious. Rewriting the same resume 50 times a day shouldn't be. **AI Resume Coach** solves this by bridging the gap between your resume and the job description.

Simply paste your resume text and the job description URL. The AI (powered by Google Gemini) will act as an ATS (Applicant Tracking System) expert, highlighting missing keywords, rephrasing bullet points, and suggesting specific gaps to fill.

## ✨ Features

- **🔍 AI-Powered Analysis:** Scans your resume vs. the job description to find hidden gaps.
- **✍️ Smart Rewriting:** Suggests ATS-friendly rewrites for your bullet points.
- **🚀 One-Click Tailoring:** Get an optimized version of your resume ready to copy/paste.
- **⚡ Blazing Fast:** Built on Vercel's edge network for instant feedback.
- **🔒 Privacy First:** No data storage; everything is processed temporarily via API.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Flask (Python)
- **AI Model:** Google Gemini API (Gemini 1.5 Flash/Pro)
- **Deployment:** Vercel (Serverless Functions)
- **Version Control:** Git & GitHub

## 🚀 Getting Started

To run this project locally, follow these steps.

### Prerequisites

- Python 3.8+
- A [Google AI Studio API Key](https://makersuite.google.com/app/apikey) (Free tier available)

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/[YOUR_USERNAME]/ai-resume-coach.git
    cd ai-resume-coach
**2. Set up environment variables**
Create a .env file in the root directory and add your API key:

env
GEMINI_API_KEY=your_google_api_key_here
**3. Run the application**

bash
python app.py
Note: Adjust the run command based on your main application file structure.

**4. Open http://localhost:5000 in your browser.**

**🤝 Contributing**
Contributions are welcome! If you have a suggestion that would make this better, please fork the repo and create a pull request.

1. Fork the Project

2. Create your Feature Branch (git checkout -b feature/AmazingFeature)

3. Commit your Changes (git commit -m 'Add some AmazingFeature')

4. Push to the Branch (git push origin feature/AmazingFeature)

5. Open a Pull Request

**📜 License**
Distributed under the MIT License. See LICENSE for more information.

**🙏 Acknowledgments**
Google Gemini API
Vercel
