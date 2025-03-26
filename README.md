Context Aware Testing System for Financial Ecosystems

## 📌 Table of Contents
- Introduction
- Inspiration
- What It Does
- How We Built It
- Challenges We Faced
- How to Run
- Tech Stack
- Team

---

## 🎯 Introduction
Our project is a Context Aware Testing System for Financial Ecosystems. It's a system that can
dynamically generates test scenarios leveraging LLM(Gemini) based on contextual inputs to simulate real-world usage and edge cases effectively.

## 💡 Inspiration
We were inspired by the complexity and critical nature of modern financial ecosystems, where a single overlooked edge case can result in system failures, financial losses, or regulatory issues. Manual test case creation is time-consuming and often lacks contextual depth, especially in systems that evolve rapidly.

## ⚙️ What It Does
A system that could understand the business context, analyze backend logic, and generate intelligent test scenarios using LLMs like Gemini. By automating the generation of BDD-style test cases, our system enables QA teams and developers to simulate real-world usage and edge cases at scale — reducing human effort while increasing test coverage and reliability.

## 🛠️ How We Built It
We used ReactJs and Python along with gemini API and GitHub api

## 🚧 Challenges We Faced
LLM Limitations: At times, the Gemini model would hallucinate or generate vague steps
GitHub integration: Pulling code recursively from repositories and filtering relevant files  introduced challenges in performance and API rate-limiting.

## 🏃 How to Run
1. Clone the repository  
2. Install dependencies  
   pip install flask dotenv google_generativeai 
   npm install 
3. Create your personal access github token for accessing github apis
4. Create an .env in code/src/backend folder and paste your personal access token. 
   GITHUB_TOKEN = <token>
5. Run the project  
   Backend- python main.py
   Frontend- npm run dev
   

## 🏗️ Tech Stack
- 🔹 Frontend: ReactJs
- 🔹 Backend: Python/ FastAPI /
- 🔹 Other: Gemini API / GitHub API

## 👥 Team
- **Kashish Agarwal** 
- **Sivam Das** 
- **MD Asif** 
- **Prashanth Chowdary**
