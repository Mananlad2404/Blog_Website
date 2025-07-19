# 📝 Blog Website

A full-stack **Blog Website** developed using **Node.js**, **Express.js**, **EJS**, **MongoDB**, and **JavaScript**, designed for users to **read, post, edit, and manage blog content**. It supports **user authentication**, **admin dashboard**, **responsive UI**, and **search functionalities**.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Screenshots](#screenshots)
- [How to Run](#how-to-run)

---

## 📖 About the Project

In today's digital world, blogs are essential for information sharing, community building, and self-expression. This project serves as a dynamic hub for users to **publish blogs**, **engage with content**, and **manage their posts** through a clean, responsive interface.

The project was developed as a part of the **4th Semester Project-II (CSE210)** at **DEPSTAR, CHARUSAT**, under the guidance of **Dr. Krishna Patel**.

---

## ✨ Features

- 🧾 User registration & login
- 🔐 Admin authentication
- 📝 Add/Edit/Delete blog posts
- 🗂 Categorization & tagging
- 🔍 Search functionality
- 🖼 Upload blog images
- 📱 Fully responsive design
- 📨 Contact page for queries

---

## 🛠 Tech Stack

**Frontend**:

- HTML, CSS, JavaScript
- EJS Templating Engine

**Backend**:

- Node.js
- Express.js

**Database**:

- MongoDB

**Others**:

- Git & GitHub
- VS Code

---

## 📁 Folder Structure

```
Blog_Website/
│
├── node_modules/
├── public/
│ ├── css/
│ │ └── style.css
│ └── img/
│ ├── hero-image.webp.png
│ └── img-noise-361x370.png
│
├── js/
│ └── script.js
│
├── server/
│ ├── config/
│ │ └── db.js
│ ├── helpers/
│ │ └── routeHelpers.js
│ ├── models/
│ │ ├── Post.js
│ │ └── User.js
│ └── routes/
│ ├── admin.js
│ └── main.js
│
├── views/
│ ├── admin/
│ │ ├── add-post.ejs
│ │ └── dashboard.ejs
│ ├── layouts/
│ │ ├── admin.ejs
│ │ └── main.ejs
│ ├── partials/
│ │ ├── contact.ejs
│ │ ├── footer.ejs
│ │ ├── header.ejs
│ │ ├── header_admin.ejs
│ │ ├── search.ejs
│ ├── edit-post.ejs
│ ├── index.ejs
│ ├── post.ejs
│ └── search.ejs
│
├── .env
├── .gitignore
├── app.js
├── package.json
└── package-lock.json
```

---

## 🖼️ Screenshots

> (You can add screenshots here using: `![Alt Text](path-to-image)`)

- Home Page
- Admin Login Page
- Admin Dashboard
- Blog Post Page

---

## 🚀 How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/Mananlad2404/Blog_Website.git
   cd Blog_Website
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Setup environment variables in .env:
   ```bash
   MONGODB_URI=your_mongodb_connection_string
   PORT=5000
   ```
4. Run the app:
   ```bash
   npm run dev
   ```
