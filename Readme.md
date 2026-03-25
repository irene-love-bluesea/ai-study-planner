# 🧠 AI Study Planner

## 📌 Introduction

AI Study Planner is a full-stack web application designed to help students plan and optimize their study schedules intelligently.

The system allows users to upload course syllabi in PDF format, automatically extracts structured topics using AI, and generates a personalized study plan based on subject difficulty, estimated effort, and available time.

Unlike traditional planners, this application combines algorithmic scheduling with AI-assisted analysis to provide a smarter and more adaptive learning experience.

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- TailwindCSS
- Chart.js / Recharts

### Backend
- Node.js
- Express.js
- JWT Authentication

### Database
- MongoDB (Mongoose)

### AI Integration
- OpenAI API (LLM)
- PDF text extraction (`pdf-parse`)

### Deployment
- Vercel (Frontend)
- Render / Railway (Backend)

---

## ⚙️ Features

### 📄 AI Syllabus Analysis
- Users can upload PDF syllabi for each subject
- The system extracts raw text from the PDF
- AI processes the content and returns:
  - Main topics
  - Subtopics
  - Difficulty levels (1–5)
  - Estimated study hours per topic
- Structured data is stored in the database for further processing

---

### 🧠 Study Plan Generation
- A custom scheduling algorithm calculates priority for each topic:
  
