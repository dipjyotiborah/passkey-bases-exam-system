<div align="center">
  <h1>🚀 Passkey Based Exam System</h1>
  <p>
    A secure and scalable online examination platform with passkey-based access, built using React.js and Node.js
  </p>

<!-- Badges -->
<p>
  <img src="https://img.shields.io/badge/status-active-success.svg" />
  <img src="https://img.shields.io/badge/version-1.0-blue.svg" />
  <img src="https://img.shields.io/badge/license-open--source-lightgrey.svg" />
</p>

<h4>
    <a href="#">View Demo</a>
  <span> · </span>
    <a href="https://github.com/dipjyotiborah/passkey-bases-exam-system/issues">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/dipjyotiborah/passkey-bases-exam-system/issues">Request Feature</a>
</h4>
</div>

<br />

# 📖 Table of Contents

- [About the Project](#about-the-project)
  * [Tech Stack](#tech-stack)
  * [Features](#features)
  * [Environment Variables](#environment-variables)
- [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Run Locally](#run-locally)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## ⭐ About the Project

The **Passkey Based Exam System** is a modern web application designed to conduct secure online examinations. It uses a **unique passkey mechanism** to ensure only authorized users can access exams.

Ideal for:
- Educational institutions (schools, colleges, NIELIT centers)
- Training institutes
- Certification platforms

---

## 🛠 Tech Stack

<details>
  <summary>Frontend</summary>
  <ul>
    <li>React.js</li>
    <li>Redux</li>
    <li>Material UI</li>
    <li>HTML5 & CSS3</li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li>Node.js</li>
    <li>Express.js</li>
    <li>REST API</li>
  </ul>
</details>

<details>
  <summary>Database</summary>
  <ul>
    <li>MongoDB</li>
  </ul>
</details>

---

## 🎯 Features

### 👨‍🎓 Student
- Login & Registration
- Enter exam using secure passkey
- Attempt MCQ-based exams
- View results instantly
- Answer review system

### 👩‍🏫 Teacher
- Create & manage question banks
- Generate exams with passkeys
- Monitor student performance

### 🛠 Admin
- Manage users (students & teachers)
- Manage subjects and exams
- Full system control

---

## 🔐 Environment Variables

Create file:
backend/config.json


Add:

```json
{
  "mongodb": {
    "connectionString": "your_mongodb_url"
  },
  "jwt": {
    "secret": "your_secret_key"
  }
}
🧰 Getting Started
⚠️ Prerequisites
Node.js installed
MongoDB installed and running
▶️ Run Locally

Clone the project:

git clone https://github.com/dipjyotiborah/passkey-bases-exam-system.git
cd passkey-bases-exam-system

Install dependencies:

cd backend && npm install
cd ../frontend && npm install
cd ../user-portal-frontend && npm install

Start backend:

cd backend
npm start

Start frontend:

cd frontend
npm start

Start user panel:

cd user-portal-frontend
npm start
🌐 Application URLs
Backend: http://localhost:5000
Admin Panel: http://localhost:3100
User Panel: http://localhost:3200
🚀 Future Improvements
AI-based proctoring system
Timer with auto-submit
Mobile app version
Advanced analytics dashboard
🤝 Contributing

Contributions are welcome!

Fork the repository
Create a new branch
Make your changes
Submit a Pull Request
📄 License

This project is open-source and free to use for educational purposes.

📬 Contact

Dipjyoti Borah
IT Faculty, NIELIT Majuli

📧 yourdipjyoti@gmail.com

🔗 https://github.com/dipjyotiborah

⭐ Support

If you found this project useful:

Give it a ⭐ on GitHub
Share with others
