# 📚 ReRead – Online Book Exchange Platform

## 📖 Overview

ReRead is a full-stack web application developed as a mini project using PHP and MySQL. The platform allows users to exchange books, discover books shared by others, communicate through a community forum, and manage book requests. An admin panel is included to moderate users, approve book listings, and manage community activities.

---

## ✨ Features

### User Features
- User Registration and Login
- Browse and Search Books
- View Book Details
- Add Books to Wishlist
- Shopping Cart Management
- Community Discussion
- Notifications
- User Profile Management
- Password Recovery
- Email Verification

### Admin Features
- Admin Dashboard
- Book Approval and Management
- Community Moderation
- User Management
- Report Handling
- Email Notifications

---

## 🛠️ Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript
- Bootstrap

**Backend**
- PHP

**Database**
- MySQL

**Server**
- XAMPP / Apache

**Version Control**
- Git & GitHub

---

## 📂 Project Structure

```
ReRead/
│
├── admin/
│   ├── adminpage/
│   ├── emailvalid/
│   └── ...
│
├── user/
│   ├── login/
│   ├── products/
│   ├── community/
│   ├── cart/
│   ├── wishlist/
│   ├── notifications/
│   └── profile/
│
├── commonconnect.php
├── userinfo (27).sql
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/meringeo1011-coder/miniproject.git
```

### 2. Move the Project

Copy the project folder into your XAMPP `htdocs` directory.

Example:

```
C:\xampp\htdocs\miniproject
```

### 3. Create Database

Create a database named:

```
userinfo
```

### 4. Import Database

Import the SQL file:

```
userinfo (27).sql
```

using phpMyAdmin.

### 5. Configure Database Connection

Update `commonconnect.php` if necessary.

```php
$connection = new mysqli("localhost", "root", "", "userinfo");
```

---

## 🚀 Running the Project

Start Apache and MySQL using XAMPP.

Open your browser and visit:

### User Login

```
http://localhost/miniproject/user/login/login.php
```

### User Signup

```
http://localhost/miniproject/user/login/signup/signup.php
```

### Admin Dashboard

```
http://localhost/miniproject/admin/adminpage/adminhome.php
```

---

## 👤 Admin Credentials

**Username**

```
rereadadmin1
```

**Password**

```
rereadadmin@123
```

---





## 🔮 Future Enhancements

- AI-based Book Recommendation System
- Online Payment Integration
- Mobile Responsive Design
- Real-Time Notifications
- Chat System
- QR Code Based Book Exchange

---

## 📄 License

This project was developed for educational purposes as part of an Integrated MCA Mini Project.

---

## 👩‍💻 Author

**Merin Geo**

GitHub: https://github.com/meringeo1011-coder
