# 📝 Online Exam System - Tiru Ram Narla

An advanced **Django-based web application** to conduct secure, dynamic online examinations with fraud detection and leaderboard functionality.

## 📌 Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots) *(optional)*
- [License](#license)

---

## 🚀 Features
- 🔐 User authentication (login, logout, registration)
- 🧠 Dynamic online exams with question shuffling
- 🏆 Leaderboard displaying top scorers
- 🚨 Fraud detection system for login integrity
- 📊 Score evaluation and display

---

## ⚙️ Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/krishnateja-81/QUIZ-APP
Navigate to the project directory

bash
Copy
Edit
cd online-exam-system
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Apply migrations

bash
Copy
Edit
python manage.py makemigrations
python manage.py migrate
Create a superuser (admin access)

bash
Copy
Edit
python manage.py createsuperuser
Start the development server

bash
Copy
Edit
python manage.py runserver
Access the app
Open your browser and go to:
http://127.0.0.1:8000

🧑‍💻 Usage
🔐 User Authentication:
Register with a username, password, full name, and email.

Log in to begin the exam.

📝 Conducting Exam:
Once logged in, users are taken to the exam dashboard.

Questions are randomly shuffled for each session.

Submit your answers to receive a score.

🏆 Leaderboard:
View your ranking and top 10 scorers after submission.

Scores are updated in real-time.

🚨 Fraud Detection:
Fraud attempts during login are monitored.

If detected, access is revoked, and the user is logged out immediately.

📷 Screenshots
(Optional: Add screenshots of login, exam page, leaderboard, and fraud detection page here)

🧑 Author
Tiru Ram Narla
Passionate about building secure and scalable web applications with Python and Django.

📄 License
This project is open-source and available for non-commercial use. Attribution is appreciated.

python
Copy
Edit

---

Let me know if you'd like me to:
- Customize this for deployment on a cloud server
- Add badges (like build status, license, etc.)
- Include preview images in Markdown

I'm happy to help!
