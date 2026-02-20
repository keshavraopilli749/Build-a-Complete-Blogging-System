# 📝 Blogging System – Django Project

A full-featured Blogging System built using **Django** with authentication, role-based dashboards, search functionality, and deployment-ready configuration.

---

## 🚀 Features

### 📰 Blog Management

* Create, Edit, Delete Blog Posts
* Unique Slug-based URLs
* Featured Posts
* Recent Articles Section
* Blog Image Upload (Media Handling)

### 📂 Category Management

* Add, Edit, Delete Categories
* Posts filtered by Category
* Category-wise blog listing

### 🔐 Authentication System

* User Registration
* Login & Logout
* Role-based Access Control
* Django Groups & Permissions

### 🏢 Dashboard System

* Manager Dashboard
* Editor Dashboard
* Blog & Category Count
* Role-based content visibility

### 💬 Comment System

* Authenticated users can comment
* Blog-specific comments
* Reverse relationship handling

### 🔎 Search Feature

* Search blogs by title/content
* Retains search term in textbox

### 🎨 Frontend

* Template Inheritance
* Static Files Configuration
* Custom 404 Page
* Sidebar Navigation & Active Highlighting

### 🚀 Deployment Ready

* Production settings checklist
* Media & Static handling
* Git version control integration

---

## 🛠 Tech Stack

* **Backend:** Django
* **Database:** SQLite (Development) / PostgreSQL (Production Ready)
* **Frontend:** HTML, CSS, Bootstrap
* **Authentication:** Django Built-in Auth System
* **Version Control:** Git & GitHub

---

## 📁 Project Structure

blogging-system/
│
├── blog_main/
├── blogs/
├── dashboards/
├── templates/
├── static/
├── media/
├── manage.py
└── requirements.txt

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

https://github.com/keshavraopilli749/Build-a-Complete-Blogging-System

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Create Superuser

```bash
python manage.py createsuperuser
```

### 6️⃣ Run Server

```bash
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000/
```

---

## 🧠 Key Concepts Implemented

* Model Relationships (ForeignKey)
* Slug Generation
* Role-Based Authorization
* Reverse Querying
* Query Optimization with ORM
* Context Processors
* Custom Error Pages
* Login Required Decorator
* Unique Slug Handling

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Designing relational database models
* Implementing authentication & authorization
* Managing media & static files
* Creating SEO-friendly URLs using slugs
* Implementing role-based dashboards
* Deploying Django applications

---

## 🔮 Future Improvements

* REST API Integration
* JWT Authentication
* Like/Bookmark Feature
* Pagination
* Docker Deployment
* Cloud Deployment (Render / AWS)

---

## 👨‍💻 Author
P.Keshav Rao

# ⭐ If you like this project, give it a star!


