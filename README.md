# 🎓 CGPA Calculator

A simple and interactive CGPA calculator built with **React (Vite)** for the frontend and **PHP + MySQL** for the backend.  
It allows students to input their marks or grades and automatically calculates the CGPA with real-time updates.

LIVE DEMO  https://delicate-cat-8ba2c5.netlify.app/

## 📁 Project Structure

CGPA/
├── backend/
│ ├── api/
│ │ ├── db.php
│ │ ├── save_cgpa.php
│ │ ├── store.php
│
├── frent/ (Frontend)
│ ├── vite-project/
│ │ ├── public/
│ │ ├── src/
│ │ │ ├── assets/
│ │ │ ├── App.css
│ │ │ ├── App.jsx
│ │ │ ├── CGPAForm.jsx
│ │ │ ├── index.css
│ │ │ ├── main.jsx
│ │ ├── package.json
│ │ ├── vite.config.js
│
├── README.md


---

## ⚙️ Features

- Add and edit subjects with marks.
- Converts marks into GPA automatically.
- Calculates average CGPA dynamically.
- Option to save data using backend PHP scripts.
- Clean and responsive UI built with React + Vite.

---

## 🧩 Tech Stack

**Frontend:** React, Vite, CSS  
**Backend:** PHP  
**Database:** MySQL  
**Server:** XAMPP / WAMP / Localhost

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/CGPA.git
cd CGPA/frent/vite-project

2. Install frontend dependencies
npm install

3. Run the frontend
npm run dev

4. Setup backend

Copy the backend folder into your htdocs (if using XAMPP).

Create a database in phpMyAdmin (e.g. cgpa_db).

Import your tables or create one for storing results.

Make sure your db.php file has correct credentials:

$conn = new mysqli("localhost", "root", "", "cgpa_db");

5. Test the app

Open your browser and visit:

http://localhost:5173

🧠 How It Works

User enters registration number, name, and marks.

Marks are converted to GPA using a simple formula.

The app averages all GPAs to calculate the CGPA.

Data can optionally be saved to the database using PHP API.

🪪 Author

Feroz khan
Social Media Ads Specialist & Web Developer
