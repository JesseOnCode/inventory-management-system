# Inventory Management System (Demo)

This is a demo inventory management system built as a portfolio project.

The application demonstrates:
- User authentication
- Role-based access control (Admin / Demo)
- Basic inventory management (Add, View, Delete)
- Secure public demo setup

---

## 🚀 Features

- Login system with two roles:
  - **Admin** – full access
  - **Demo** – limited access
- Product list with stock amounts
- Add new products (Admin & Demo)
- Delete products (Admin only)
- Session-based demo data (resets on logout)

---

## 🔐 Demo Accounts

| Role  | Username | Password |
|------|----------|----------|
| Admin | admin | admin123 |
| Demo | demo | demo123 |

⚠️ Note:  
This is a **public demo application**.  
All product data is stored in the session and will reset on logout to prevent permanent changes.

---

## 🛠️ Tech Stack

- PHP
- HTML
- CSS
- JavaScript
- MySQL (planned)
- XAMPP (Apache)

---

## 📁 Project Structure

/public
├── index.php
├── login.php
├── logout.php
├── products.php
└── css/style.css

---

## 📌 Why session-based storage?

This demo uses PHP sessions instead of a database to:
- Keep the public demo safe
- Prevent data abuse
- Clearly demonstrate business logic

A database-backed version can be added as a next step.

---

## 👤 Author

Jesse Haapaniemi  
GitHub: https://github.com/JesseOnCode