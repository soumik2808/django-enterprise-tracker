# Django Enterprise Tracker

A modular and extensible enterprise-level internal tracking system, built using Django.  
Inspired by real-world enterprise tooling needs from past experiences at Accenture, Oracle, and UCI.

---

## 🔧 Modules Overview

### 1. `employees/`

- Manages employee profiles, roles, and departments.
- Future features: role-based permissions, user onboarding workflow.

### 2. `leaves/`

- Leave request, approval, and tracking system.
- Tracks leave balance and logs leave history.

### 3. `messaging/`

- Internal messaging between employees.
- Notification templates and alert systems planned.

---

## 🧱 Technology Stack

- **Backend:** Django (Python)
- **Frontend:** HTML/CSS (Django templates), Bootstrap (planned)
- **Database:** SQLite (default for now, can be upgraded to PostgreSQL)
- **Other tools planned:** Django Rest Framework (DRF), Docker (for containerization)

---

## 📂 Folder Structure

```text
django-enterprise-tracker/
│
├── employees/          # Handles employee data
├── leaves/             # Leave application and approval system
├── messaging/          # Internal messaging system
├── static/             # Static files like CSS/JS/images
├── templates/          # HTML templates
└── README.md
```

🔒 Disclaimer
This project simulates enterprise tools and workflows based on my past experience during second half of my Accenture days with confidential client projects.
Original work done with clients like Oracle or Accenture internal have been simulated to the best possible way.
Hence, dummy data and functionality have been used in this repository for learning and demonstration purposes.

✅ To-Do (Upcoming Enhancements)
Initialize Django project and apps

Create database models for all modules

Build a basic admin interface for HR

Integrate login/auth system

REST APIs using DRF

Containerize the app with Docker
