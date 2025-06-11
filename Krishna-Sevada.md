# 📊 Project Scope: Task Tracker

---

## 📌 Project Overview

**Task Tracker** is a full-stack web application designed to help users plan, manage, and track their weekly tasks. The system also includes an admin role to monitor and manage all users' tasks and their statuses.

---

## 🎯 Core Functionalities

### ✅ User Functionalities

Login and Registration
Plan tasks for the week
Update task status: Pending, In Progress, Completed
View:
  - Total tasks for the current week
  - Remaining tasks for the week
  - Completed tasks for the week
  - All tasks for the week

### 🛡 Admin Functionalities

Admin dashboard with access to:
  - All users' tasks
  - View task statuses for any user
Ability to filter tasks by user and by status

---

## 🔧 Tech Stack

**Frontend:** React.js
**Backend:** Node.js + Express.js
**Database:** MySQL or PostgreSQL
**Authentication:** JWT

---

## 🔐 Authentication & Roles

JWT-based authentication
Two roles: User and Admin
Role-based access control for protected routes

---

## 📝 Task Management Features

Create tasks
  - Task title
  - Description (optional)
  - Due date (week-based)
  - Status (default: Pending)
Edit tasks
Delete tasks
Update task status
Filter tasks by week, status, and user (for admin)

---

## 🌐 Frontend Pages

Login page
Registration page
User dashboard
  - Weekly summary (total tasks, completed, pending)
  - List of all tasks for the current week
Admin dashboard
  - All tasks view across users
  - Filtering by user and status

---

## 🔒 Security

Password encryption (bcrypt)
JWT token for secure sessions
Role-based access control (admin vs user)
Input validation
Data access restrictions based on role

---

## 📈 Deliverables

Fully functional full-stack Task Tracker application
Role-based authentication and authorization
Weekly planning and tracking of tasks
Admin access to full system data
SQL
 database to store users & tasks

---
