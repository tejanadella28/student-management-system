# 🎓 Student Management System

A **modern Django-based Student Management System** with a **clean, responsive, and beautiful UI**, designed to simplify managing student records, classes, and academic activities.

---

## 🚀 Features
- 🔐 **Role-Based Access Control** – Admin, Teacher, and Student logins
- 📚 **Student CRUD Operations** – Add, edit, delete, and view student data
- 🏫 **Class & Subject Management**
- 📊 **Responsive Dashboard** – Overview of all key stats
- 🎨 **Attractive & User-Friendly UI**
- 🔄 **Easily Extensible** – Add attendance, grades, or reports modules

---

## 🖼️ Screenshots

| Home Page | Teacher Login | Student Login |
|-----------|---------------|---------------|
| ![Home Page](https://github.com/tejanadella28/student-management-system/blob/main/Screenshot%202025-08-10%20145850.png?raw=true) | ![Teacher Login](https://raw.githubusercontent.com/tejanadella28/student-management-system/main/Screenshot%202025-08-10%20145907.png) | ![Student Login](https://github.com/tejanadella28/student-management-system/blob/main/Screenshot%202025-08-10%20145926.png?raw=true) |

---

## 🛠 Tech Stack
- **Backend:** [Django](https://www.djangoproject.com/) (Python)
- **Frontend:** HTML5, CSS3, Bootstrap
- **Database:** SQLite (default) or any Django-supported DB
- **Version Control:** Git & GitHub

---

## 📥 Installation

```bash
# 1️⃣ Clone the repository
git clone https://github.com/tejanadella28/student-management-system.git
cd student-management-system

# 2️⃣ Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Apply migrations
python manage.py migrate

# 5️⃣ Create superuser
python manage.py createsuperuser

# 6️⃣ Start the server
python manage.py runserver
