# 🎯 Quiz Management Platform
---
## 🧩 Summary

This project is a dynamic quiz web application built using PHP, MySQL, HTML, CSS, and JavaScript. It supports both admin and user panels. Admins can manage courses, tasks, and questions, while users can register, take quizzes, and view/download results.

---

## 🧪 Tech Stack

- PHP
- MySQL
- HTML5
- CSS3
- JavaScript

---

## ⚙️ Features

### 👨‍🏫 Admin Panel
- Admin login/register
- Manage Courses
- Manage Tasks (quizzes)
- Manage Questions
- Dashboard overview

### 👨‍🎓 User Panel
- User registration/login
- View available courses
- Take quizzes by task
- Resume incomplete tasks
- View task-level and course-level results
- Export results as CSV

---

## 🔁 How It Works

1. **Admin** logs in and creates:
   - Courses (e.g., Python, Java)
   - Tasks under each course
   - Questions under each task

2. **Users**:
   - Register and log in
   - View courses → choose tasks
   - Start/Resume quizzes
   - Submit answers
   - View results with breakdown
   - Download results as `.csv`

---
## 🔐 User Roles

- **Admin**: Manage content & monitor performance
- **User**: Take quizzes, track progress, export reports

---


## 📁 File Exports

- CSV download for:
  - Each task (user answers + correct answers)
  - Entire course summary

---
## 📤 How to Run

1. Clone this repo or upload it to your server.
2. Import `quiz.sql` into your MySQL database.
3. Update `db.php` with your DB credentials.
4. Run `localhost/project-folder/users` or `admin`.
---
## 📎 Future Scope

- Add timer for tasks
- Visual analytics (score charts)
---

## 📧 Author

> Built by **Sai Harsha Pabolu**
