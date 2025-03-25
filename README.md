# 🚀 Laravel Blog Application with Authentication

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

A complete blog application with user authentication and secure CRUD operations built with Laravel and Tailwind CSS.

## ✨ Features

- **🔐 Authentication System**
  - User registration and login
  - Password hashing with bcrypt
  - Protected routes with middleware

- **📝 Blog Management**
  - Create, Read, Update, Delete posts
  - Rich text editing capabilities
  - User-specific post ownership

- **🛡️ Security Features**
  - 🛡️ CSRF protection on all forms
  - 🔒 Bcrypt password hashing
  - 🚫 SQL injection prevention
  - ✂️ XSS protection


- **🎨 Modern UI**
  - Responsive design with Tailwind CSS
  - Clean, intuitive interface
  - Dark mode support

## 📦 Installation

### Prerequisites
- PHP 8.0+
- Composer
- Node.js 14+
- MySQL 5.7+

### Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/laravel-blog.git
cd laravel-blog
```

### Install Dependencies
```bash
composer install
npm install
```
### Setup Database
```bash
php artisan migrate
```

### Running the Application
Start the development server:
```bash
php artisan serve
```

