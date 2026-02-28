# SkillBridge AI
## AI-Based Skill Gap Identification System 
SkillBridge AI is an AI-powered platform that analyzes resumes to identify skill gaps and provides personalized learning recommendations.

[![express](https://img.shields.io/badge/Express.js-4.19.2-orange?style=for-the-badge&logo=express)](https://www.npmjs.com/package/express) [![cors](https://img.shields.io/badge/CORS-2.8.5-blue?style=for-the-badge)](https://www.npmjs.com/package/cors)  [![dotenv](https://img.shields.io/badge/Dotenv-16.4.5-green?style=for-the-badge)](https://www.npmjs.com/package/dotenv)  [![nodemon](https://img.shields.io/badge/Nodemon-3.1.0-yellow?style=for-the-badge)](https://www.npmjs.com/package/nodemon)

## Features

- Resume analysis for PDF, DOCX, and TXT files
  
- Skill gap detection vs job requirements
  
- Course and certification recommendations

- AI chatbot for career guidance and interview prep

- Secure processing with privacy protection

## Project Structure

```
skill-gap-analyzer/
├─ index.html               ← Main app (open this)  
├─ manifest.json            ← PWA manifest  
├─ favicon.png              ← App icon  
├─ package.json  

├─ css/  
│   ├─ vendors.css          ← Reset styles  
│   └─ main.css             ← Full app design  

├─ js/  
│   ├─ skillDatabase.js     ← All skills, jobs, courses, chatbot KB  
│   ├─ app.js               ← Main orchestrator  
│   ├─ resumeUpload.js      ← Drag & drop + validation  
│   ├─ resumeParser.js      ← PDF/DOCX/TXT text extraction  
│   ├─ skillAnalysis.js     ← NLP skill detector  
│   ├─ jobMatching.js       ← Match scoring engine  
│   ├─ recommendations.js   ← Course recommender  
│   ├─ chatbot.js           ← AI career guide  
│   └─ progressBar.js       ← Animated progress bars  

├─ backend/                 ← Optional Node.js backend  
│   ├─ server.js  
│   ├─ routes/  
│   └─ utils/  

├─ config/  
│   └─ frontend-config.js   ← App configuration  

└─ assets/  
    └─ logo_v3.png
```

## Installation and Run

### 1. Clone the repository (or download the project files)
```
git clone https://github.com/ishwarya100/SkillBridge-AI.git
cd SkillBridge-AI
```
### 2. Install dependencies
```
npm install
```
### 3. Run the server:
```
npm run dev   # for development with auto-reload
npm start     # for production
```
### 4. Open index.html in your browser to use the app.



## How It Works

- Upload your resume (PDF, DOCX, or TXT).
  
- System validates file type and content.
   
- Extracts skills, experience, and education.
   
- Detects skill gaps against job requirements.
  
- Recommends courses and certifications.
   
- Chatbot provides career guidance.

- Dashboard shows results and progress visually.  


____________________________________________________________________________________________________________________________
*Thanks for checking out SkillBridge AI :)*


**Upload your resume and explore your skill gaps today!**

