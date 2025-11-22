# Word-to-PDF Converter 🔄📄➡️📑

A simple and powerful full-stack Word (.doc/.docx) to PDF converter built using:

- React (Frontend UI/UX)
- Node.js + Express.js (Backend file processing)
- Multer for file uploads
- PDF conversion library (docx-pdf / libreoffice-convert)

This tool allows users to upload Word files and download clean PDF files directly from the browser.

------------------------------------------------------------

## 🚀 Features

- Convert .doc / .docx → .pdf
- Full-stack architecture (React + Node.js)
- Clean API communication
- File upload using Express + Multer
- Download PDF as a blob from frontend
- Responsive UI with Tailwind CSS
- Beginner-friendly code structure

------------------------------------------------------------

## 📂 Project Structure

WordToPdf/
   frontend/
      src/
      public/
      package.json
   backend/
      server.js
      routes/
      controllers/
      package.json

------------------------------------------------------------

## 🔧 Tech Stack

Frontend:
- React
- Tailwind CSS
- Axios

Backend:
- Node.js
- Express.js
- Multer
- docx-pdf / libreoffice-convert

------------------------------------------------------------

## ⚙️ Run the Project Locally

1️⃣ Clone the repo:
git clone https://github.com/RajRajeshwar8863/WordToPdf
cd WordToPdf

------------------------------------------------------------

2️⃣ Setup Backend:
cd backend
npm install
npm start

Backend will run on:
http://localhost:5000

------------------------------------------------------------

3️⃣ Setup Frontend:
Open NEW terminal:
cd frontend
npm install
npm start

Frontend will run on:
http://localhost:3000

------------------------------------------------------------

## 📤 How It Works

1. User uploads a .doc or .docx file
2. Frontend sends file to Node.js API
3. Backend converts file to PDF
4. Frontend receives PDF blob and automatically downloads it

------------------------------------------------------------

## 🙌 What I Learned

- Frontend ↔ Backend API communication
- Handling file uploads in Express.js
- Returning PDF blobs to frontend
- Structuring a full-stack project
- Building responsive UI with Tailwind

------------------------------------------------------------

## 🎯 Future Improvements

- Multiple file conversion
- Drag-and-drop upload UI
- Conversion history
- Deployment on Render / Vercel

------------------------------------------------------------

## 🧑‍💻 Author

**Raj Rajeshwar**  
👉 Aspiring Full-Stack Developer | DSA Practitioner | Always building 🚀

------------------------------------------------------------

## ⭐ If this project helped you, consider giving it a star!
