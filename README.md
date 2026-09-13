# 🧪 LabNexa

A modern, role-based **Laboratory Equipment Management System** built using **Flask** and **MySQL**. LabNexa streamlines laboratory equipment booking, approval workflows, inventory management, analytics, and PDF report generation through a clean and responsive web interface.

---

# 📌 Overview

LabNexa is a full-stack web application developed to simplify the management of laboratory equipment in educational institutions.

The system provides separate dashboards and permissions for **Students**, **Faculty**, and **Administrators**, ensuring secure and organized management of laboratory resources.

---

# 🌟 Project Highlights

- 🔐 Secure Authentication with Password Hashing
- 👥 Role-Based Access Control
- 📦 Equipment Management (CRUD)
- 👤 User Management (CRUD)
- 🔍 Equipment Search & Smart Filters
- 📊 Interactive Booking Analytics Dashboard
- 📄 Downloadable PDF Reports
- 📱 Responsive User Interface
- 🛡️ Session-Based Authentication

---

# ✨ Features

## 👨‍🎓 Student Module

- Secure Registration & Login
- Browse Available Equipment
- Search Equipment
- Filter by Category
- Filter by Availability
- Book Laboratory Equipment
- View Booking History
- Track Booking Status

---

## 👨‍🏫 Faculty Module

- Secure Login
- View Equipment Requests
- Approve Booking Requests
- Reject Booking Requests

---

## 👨‍💼 Admin Module

- Admin Dashboard
- Equipment Management (CRUD)
- User Management (CRUD)
- Inventory Management
- View System Reports
- Booking Analytics Dashboard
- Generate PDF Reports

---

# 🔐 Security Features

- Password Hashing using Werkzeug
- Session-Based Authentication
- Role-Based Access Control
- Protected Routes
- Secure Login System

---

# 🛠️ Technology Stack

| Category | Technology |
|----------|------------|
| Backend | Python, Flask |
| Frontend | HTML5, CSS3, Bootstrap 5, Chart.js |
| Database | MySQL |
| Template Engine | Jinja2 |
| PDF Generation | ReportLab |
| Version Control | Git & GitHub |
| Deployment | Render |

---

# 📂 Project Structure

```text
LabNexa
│
├── static
│   ├── css
│   ├── images
│   └── screenshots
│       ├── Homepage.png
│       ├── login.png
│       ├── student-dashboard.png
│       ├── faculty-dashboard.png
│       ├── admin-dashboard.png
│       ├── manage-equipment.png
│       ├── manage-users.png
│       ├── reports.png
│       ├── booking_analytics_chart.png
│       └── pdf_report.png
│
├── templates
│
├── app.py
├── schema.sql
├── requirements.txt
├── .gitignore
└── README.md