<div align="center">

# 📚 ReRead

### Online Book Exchange Platform

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=flat&logo=xampp&logoColor=white)

</div>

---

## 📖 Overview

ReRead is a full-stack web application developed as a mini project using PHP and MySQL. Users can exchange books, discover books shared by others, communicate through a community forum and manage book requests. An admin panel lets administrators moderate users, approve book listings and manage community activity.

---

## ✨ Features

| 👤 User | 🛡️ Admin |
|---------|----------|
| Registration and login | Admin dashboard |
| Email verification and password recovery | Book approval and management |
| Browse and search books | User management |
| Book details page | Community moderation |
| Wishlist and cart | Report handling |
| Community discussion | Email notifications |
| Notifications | |
| Profile management | |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML5, CSS3, JavaScript, Bootstrap |
| Backend | PHP |
| Database | MySQL |
| Server | XAMPP (Apache) |
| Version Control | Git and GitHub |

---

## 📂 Project Structure

```
ReRead/
├── admin/
│   ├── adminpage/
│   └── emailvalid/
├── user/
│   ├── login/
│   ├── products/
│   ├── community/
│   ├── cart/
│   ├── wishlist/
│   ├── notifications/
│   └── profile/
├── commonconnect.php
├── userinfo (27).sql
└── README.md
```

---

## ⚙️ Installation

1. **Clone the repository**
```bash
   git clone https://github.com/meringeo1011-coder/miniproject.git
```

2. **Move the project** into your XAMPP `htdocs` folder, for example `C:\xampp\htdocs\miniproject`.

3. **Create the database** named `userinfo` in phpMyAdmin.

4. **Import** the `userinfo (27).sql` file into it.

5. **Check the database connection** in `commonconnect.php`:
```php
   $connection = new mysqli("localhost", "root", "", "userinfo");
```

---

## 🚀 Running the Project

Start **Apache** and **MySQL** in XAMPP, then open:

| Page | URL |
|------|-----|
| User login | `http://localhost/miniproject/user/login/login.php` |
| User signup | `http://localhost/miniproject/user/login/signup/signup.php` |
| Admin dashboard | `http://localhost/miniproject/admin/adminpage/adminhome.php` |

> 🔐 **Admin access:** an admin account is created by the imported database. Change its password after the first login. Credentials are not published in this repository.

---

## 🔮 Future Enhancements

- [ ] AI-based book recommendations
- [ ] Online payment integration
- [ ] Mobile-responsive design
- [ ] Real-time notifications
- [ ] Chat system
- [ ] QR-code-based book exchange

---

## 📄 License

This project was developed for educational purposes as part of an Integrated MCA mini project.

---

## 👩‍💻 Author

**Merin Geo**
[GitHub](https://github.com/meringeo1011-coder) · [LinkedIn](https://linkedin.com/in/merin-geo-ba3533254)
