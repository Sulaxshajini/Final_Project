# 🐄 Sunnyside Dairy Management System

> A full-featured web-based dairy management and e-commerce platform for streamlined operations, inventory control, and customer order management.

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [System Requirements](#system-requirements)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 About the Project

**Sunnyside Dairy Management System** is a web-based platform built to digitize and simplify the day-to-day operations of a dairy business. It combines an e-commerce storefront for customers with a powerful administrative dashboard for staff — covering everything from product listings and customer orders to inventory tracking and preorder management.

Whether you're managing stock levels, processing customer requests, or handling user accounts, Sunnyside provides a clean, intuitive interface to keep operations running smoothly.

---

## ✨ Features

### 🛍️ Customer Portal
- Browse and purchase dairy products online
- Place standard orders and preorders
- Manage personal account and order history
- Responsive, user-friendly interface

### 🔧 Admin Dashboard
- Manage product catalog (add, edit, delete products)
- Process and track customer orders and preorders
- Monitor and update inventory levels
- Manage user accounts and roles
- View sales reports and activity logs

---

## 🛠️ Tech Stack

| Layer      | Technology                  |
|------------|-----------------------------|
| Frontend   | HTML5, CSS3, JavaScript     |
| Backend    | PHP                         |
| Database   | MySQL                       |
| Server     | Apache (XAMPP / LAMP stack) |

---

## ⚙️ System Requirements

- **PHP** 7.4 or higher
- **MySQL** 5.7 or higher
- **Apache** web server (e.g., XAMPP, WAMP, or LAMP)
- A modern web browser (Chrome, Firefox, Edge)

---

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sulaxshajini/Final_Project.git
   ```

2. **Extract the source code**

   Unzip the file `E2240303_Source Code For Sunnyside dairy management System.zip` into your web server's root directory:
   - XAMPP: `C:/xampp/htdocs/sunnyside/`
   - LAMP: `/var/www/html/sunnyside/`

3. **Create the database**
   - Open **phpMyAdmin** (or your preferred MySQL client)
   - Create a new database named `sunnyside_db` (or as specified in the config file)
   - Import the provided `.sql` file from the project folder

4. **Configure the database connection**

   Open the database configuration file (e.g., `config.php` or `db.php`) and update the credentials:
   ```php
   define('DB_HOST', 'localhost');
   define('DB_USER', 'your_username');
   define('DB_PASS', 'your_password');
   define('DB_NAME', 'sunnyside_db');
   ```

5. **Start your server**
   - Launch Apache and MySQL via XAMPP/WAMP control panel
   - Navigate to `http://localhost/sunnyside/` in your browser

---

## 🖥️ Usage

### Customer
- Register or log in to your account
- Browse available dairy products
- Add items to cart and place orders or preorders
- Track order status from your account dashboard

### Administrator
- Log in at `http://localhost/sunnyside/admin`
- Manage products, inventory, and orders from the dashboard
- View and manage registered user accounts

---

## 📁 Project Structure

```
sunnyside/
├── admin/              # Admin panel pages and logic
├── assets/             # CSS, JS, and image files
│   ├── css/
│   ├── js/
│   └── images/
├── includes/           # Reusable PHP components (header, footer, db config)
├── pages/              # Customer-facing pages
├── config.php          # Database configuration
└── index.php           # Application entry point
```

> **Note:** The exact structure may vary — refer to the extracted source code for the actual file layout.

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please ensure your code follows consistent formatting and is well-commented.

---

## 📄 License

This project was developed as an academic final project. All rights reserved by the author.

---

## 👩‍💻 Author

**Sulaxshajini**
- GitHub: [@Sulaxshajini](https://github.com/Sulaxshajini)

---

> *Sunnyside Dairy Management System — Keeping dairy operations fresh and efficient.*
