# Student Task Manager

A full-stack web application built to help students manage assignments, deadlines, and exams efficiently.  
Developed as a personal project using the MERN stack (MongoDB, Express, React, Node.js).

---

## Features
- User registration & login using JWT and bcrypt
- Create, edit, and delete tasks with due dates
- Responsive dashboard with task status indicators
- RESTful API integration
- Session persistence using local storage
- Mobile-first UI design

---

##  Tech Stack
- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Authentication**: JWT, bcrypt
- **Version Control**: Git, GitHub
- **Deployment**: Render

---

## Authentication Flow
1. User signs up → password hashed using bcrypt.
2. Login returns JWT token stored in local storage.
3. Token is verified on protected routes (task dashboard, create/edit task).

---

## Deployment
- Deployed on Render with environment variables for secrets.
- Static frontend hosted with CI/CD GitHub integration.

---

## Folder Structure
