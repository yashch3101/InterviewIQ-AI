![React](https://img.shields.io/badge/React-19-blue)
![Node.js](https://img.shields.io/badge/Node.js-Express-green)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-success)
![Groq](https://img.shields.io/badge/LLM-Groq-purple)
![License](https://img.shields.io/badge/License-MIT-orange)

# AI Interview Platform

## Overview

AI Interview Platform is an intelligent interview preparation system that helps candidates analyze their resumes against job descriptions and generate personalized interview preparation reports.

The platform uses Large Language Models (LLMs) to evaluate a candidate's profile, identify skill gaps, estimate job-role compatibility, generate technical and behavioral interview questions, create preparation roadmaps, and generate ATS-friendly resumes tailored to specific job roles.

The goal of this platform is to help job seekers prepare more effectively for interviews by providing structured guidance based on their experience, skills, and target role requirements.

---

# Live Demo

Frontend: https://your-frontend-url.vercel.app

Backend API: https://your-backend-url.onrender.com

---

## Features

### Interview Report Generation

Generate a complete interview preparation report by analyzing:

* Resume
* Self Description
* Job Description

The report includes:

* Match Score
* Technical Interview Questions
* Behavioral Interview Questions
* Skill Gap Analysis
* Personalized Preparation Roadmap

---

### Match Score Analysis

The platform evaluates how closely a candidate's profile matches the target job role and generates a score between 0 and 100.

The score is calculated by comparing:

* Skills
* Technologies
* Experience
* Project Relevance
* Domain Knowledge

against the job requirements.

---

### Technical Interview Questions

Generate role-specific technical interview questions with:

* Question
* Interviewer Intention
* Detailed Answer Strategy

This helps candidates understand not only what may be asked but also how to answer effectively.

---

### Behavioral Interview Questions

Generate common behavioral and HR interview questions including:

* Communication-based questions
* Teamwork scenarios
* Leadership situations
* Problem-solving discussions
* Conflict resolution examples

Each question includes preparation guidance.

---

### Skill Gap Detection

Identify missing or weak skills compared to the target role.

Each gap is categorized as:

* Low Priority
* Medium Priority
* High Priority

allowing candidates to focus on the most impactful improvements.

---

### Personalized Preparation Roadmap

Generate a structured preparation plan containing:

* Daily Goals
* Topics to Study
* Practical Tasks
* Interview Preparation Activities

This roadmap provides a clear path toward interview readiness.

---

### ATS-Friendly Resume Generation

Generate professional resumes optimized for Applicant Tracking Systems (ATS).

Features:

* Job-Specific Resume Customization
* ATS Optimization
* Professional Formatting
* PDF Export Support
* Human-Like Resume Content

---

### Resume PDF Download

Candidates can download generated resumes directly as PDF documents.

---

## Tech Stack

### Frontend

* React.js
* Vite
* SCSS
* React Router

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### AI & LLM

* Groq API
* Llama 3.3 70B Versatile

### Validation

* Zod

### File Processing

* Multer
* PDF Parse

### PDF Generation

* Puppeteer

### Authentication

* JWT Authentication
* Protected Routes

---

## System Workflow

### Step 1

User uploads:

* Resume (PDF)
* Job Description

or

* Self Description
* Job Description

---

### Step 2

Backend extracts resume content using PDF parsing.

---

### Step 3

Candidate profile and job requirements are sent to the LLM.

---

### Step 4

AI generates:

* Match Score
* Technical Questions
* Behavioral Questions
* Skill Gaps
* Preparation Roadmap

---

### Step 5

Report is stored in MongoDB.

---

### Step 6

User can view the report through an interactive dashboard.

---

### Step 7

User can generate and download an ATS-friendly resume tailored to the target job.

---

## Project Structure

```text
Frontend/
│
├── src/
│   ├── features/
│   │   ├── auth/
│   │   └── interview/
│   │
│   ├── styles/
│   ├── App.jsx
│   └── main.jsx
│
Backend/
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── services/
│   └── config/
│
└── server.js
```

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/AI-Interview-Platform.git

cd AI-Interview-Platform
```

### Backend Setup

```bash
cd Backend

npm install
```

Create a `.env` file:

```env
PORT=5000

MONGODB_URI=your_mongodb_connection

JWT_SECRET=your_secret

GROQ_API_KEY=your_groq_api_key
```

Start Backend:

```bash
npm run dev
```

### Frontend Setup

```bash
cd Frontend

npm install

npm run dev
```

---

## Environment Variables

```env
PORT=

MONGODB_URI=

JWT_SECRET=

GROQ_API_KEY=
```

---

## Future Enhancements

* Voice-Based Mock Interviews
* AI Interview Simulator
* Speech Confidence Analysis
* Emotion Detection
* Real-Time Interview Evaluation
* Interview Performance Scoring
* Company-Specific Interview Preparation
* Multi-Language Support
* Resume Improvement Suggestions
* Cover Letter Generation

---

## Use Cases

This platform is suitable for:

* Students
* Freshers
* Internship Applicants
* Software Engineers
* Data Scientists
* Machine Learning Engineers
* Full Stack Developers
* Career Switchers

---

## License

This project is intended for educational and portfolio purposes.

---

## Author

Yash Chaurasia

B.Tech CSE (AI & ML)

AI / Machine Learning Enthusiast

GitHub: https://github.com/yashch3101