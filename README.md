**Summary**

This project is called AI Medical Report Simplifier.
It helps patients understand their medical reports easily. A user can either upload a file (PDF, JPG, PNG, TXT) or paste the text of the report. The system then sends this to the backend. The backend extracts important test results, checks if they are normal, low, or high, and gives a clear explanation in simple words using Gemini AI. The frontend shows the results neatly in a table with colored highlights.

**Tech Stack Used**

Frontend: React + Tailwind CSS + Lucide React Icons

Backend: Node.js + Express

Other Tools: Multer for file upload, Fetch API for server calls

**Hosting:**

Frontend on Vercel

Backend on Render

Setup

Clone the repos:

Frontend: git clone https://github.com/404chandan/Medical-AI-simplification

Backend: git clone https://github.com/404chandan/img_to_text-main

Install dependencies:

npm install


Create a .env file and add API keys (for OCR / Gemini if used).

Run locally:

Frontend: npm run dev

Backend: node server.js

Or use deployed links directly:

Frontend (UI): https://medical-ai-simplifiers.vercel.app

Backend API: https://plum-backend-main.onrender.com/analyze-report
