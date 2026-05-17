# 🎓 Smart Exam Seating Arrangement System

A full-stack web application designed to automate college exam seating arrangements, help students find their seats instantly, and reduce the manual workload of teachers and exam cell staff.

---

## 🚀 Project Overview

Every exam day, students often waste time checking notice boards, asking friends, and searching for their exam hall or seat before entering the exam room.

At the same time, teachers and exam cell staff spend hours manually preparing seating charts, assigning halls, arranging benches, checking departments, avoiding same-department seating, and creating printable sheets.

The **Smart Exam Seating Arrangement System** solves this problem by providing a digital platform where exam cell staff can upload student data, generate fair seating arrangements, create printable PDFs, and allow students to search their assigned seat using only their registration number.

This project is built as a practical college-level exam management solution using simple, efficient, and standard web technologies.

---

## ✨ Key Features

- 🔐 Admin login for exam cell staff
- 📁 Excel-based student data upload
- 🧠 Automatic seating arrangement generation
- 🏫 Hall-wise and bench-wise seat allocation
- 🔄 Shuffle option for generating fresh arrangements
- 🎯 Department/class mixing logic to reduce copying chances
- 👨‍🎓 Student seat search using registration number
- 📄 Professional A4 PDF generation for printing
- 💾 Lightweight JSON-based data storage
- 📱 Clean and responsive user interface

---

## 👥 Users of the System

### 👨‍🎓 Students

Students can enter their registration number and instantly find:

- Exam hall
- Bench number
- Seat position
- Exam name
- Exam date
- Session

### 👨‍🏫 Teachers / Exam Cell Staff

Admin users can:

- Upload student Excel files
- Enter exam and hall details
- Configure bench arrangements
- Preview seating layouts
- Shuffle seating plans
- Generate printable PDF reports

---

## 🛠️ Tech Stack

| Category | Technology |
|---------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js, Express.js |
| File Upload | Multer |
| Excel Processing | XLSX |
| PDF Generation | Puppeteer |
| Data Storage | JSON File |
| Styling | CSS, Google Fonts |

---

## 📂 Project Structure

```text
seating/
├── index.html
├── package.json
├── README.md
├── .nojekyll
│
├── frontend/
│   ├── admin.html
│   ├── admin.js
│   ├── seat-search.html
│   ├── seat-search.js
│   ├── api-config.js
│   └── style.css
│
└── backend/
    ├── server.js
    ├── uploads/
    ├── generated/
    └── data/
        └── arrangements.json
