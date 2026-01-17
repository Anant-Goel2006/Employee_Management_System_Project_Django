![logo](https://github.com/Anant-Goel2006/Employee_Management_System_Project_Django/blob/master/Screenshot%202026-01-17%20135355.png)
# 🏢 Employee Management System (EMS) using Django

A full-stack **Employee Management System** built using **Python & Django** that allows administrators to manage employee records efficiently with secure authentication and a structured backend workflow.

This project demonstrates real-world usage of Django’s **MVT architecture**, authentication system, ORM, and admin interface.

---

## 📌 Project Overview

The Employee Management System (EMS) is a web-based application designed to store, manage, and update employee information in an organization. It provides a secure admin login system and supports complete **CRUD operations** (Create, Read, Update, Delete) on employee data.

The project uses Django’s built-in features such as authentication, admin panel, ORM, and SQLite database for fast development and reliability.

---

## 🎯 Objectives

* Manage employee data digitally
* Implement secure authentication using Django
* Perform CRUD operations efficiently
* Understand Django MVT architecture
* Gain hands-on experience with backend web development

---

## 🛠️ Technologies & Tools Used

### Backend

* Python
* Django
* Django ORM
* Django Authentication System

### Frontend

* HTML
* CSS
* Bootstrap (optional)
* Django Templates

### Database

* SQLite3

### Development Tools

* VS Code
* Command Line / Terminal
* Git & GitHub

---

## 📂 Project Structure

```
EMS_Project/
│
├── manage.py
├── db.sqlite3
├── management/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── app_name/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── admin.py
│   └── forms.py
│
├── templates/
│   └── *.html
│
├── static/
│   └── css/js/images
│
└── README.md
```

---

## 🔐 Authentication Flow

Django’s built-in authentication system is used:

* Superuser is created using `createsuperuser`
* Admin logs in via `/admin/`
* Only authenticated users can manage employee data
* Passwords are securely hashed (not stored in plain text)

---

## 🔄 Application Workflow

1. User opens the application
2. Admin logs in using credentials
3. Dashboard is displayed
4. Admin can:

   * Add new employees
   * View employee records
   * Update employee details
   * Delete employees
5. Data is stored securely in SQLite database
6. Admin logs out

---

## 🔁 Detailed Project Flow (Step-by-Step)

### Step 1: User Request

* User sends a request through browser

### Step 2: URL Routing

* Django checks `urls.py`
* Routes request to correct view

### Step 3: View Processing

* View handles logic
* Interacts with models via ORM

### Step 4: Database Interaction

* ORM queries SQLite database
* Fetches or updates data

### Step 5: Template Rendering

* Data passed to HTML templates
* UI rendered and sent to browser

---

## 📊 Flowchart (Text Representation)

```
[ User ]
   ↓
[ Browser Request ]
   ↓
[ Django URLs ]
   ↓
[ Views ]
   ↓
[ Models / ORM ]
   ↓
[ SQLite Database ]
   ↑
[ Templates ]
   ↑
[ Response to User ]
```

---

## 🧩 MVT Architecture Explanation

### Model

* Defines database schema
* Handles data logic

### View

* Contains business logic
* Processes requests & responses

### Template

* Frontend UI
* Displays data dynamically

---

## ⚙️ Setup & Installation

```bash
# Clone repository
git clone <repo-url>

# Navigate to project
cd EMS_Project

# Install dependencies
pip install django

# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start server
python manage.py runserver
```

---

## 🌐 Access Application

* Admin Panel: `http://127.0.0.1:8000/admin/`
* Login using superuser credentials

---

## 🚀 Future Enhancements

* Role-based access (Admin / Employee)
* REST API integration
* Deployment on cloud (AWS / Heroku)
* Improved UI with React
* Advanced reporting & analytics

---

## 👨‍💻 Author

**Anant Goel**
B.Tech – Data Science
Passionate about Backend Development & Data Engineering

---

## ⭐ If you like this project

Don’t forget to **star ⭐ the repository** and share feedback!
