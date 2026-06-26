# 🩸 Blood Point Management System

A web-based Blood Donation Management System developed as an academic mini-project to simplify the process of donor registration, donor management, and blood group search.

The system provides a centralized platform where blood donors can register their details and users can search for available donors based on blood group requirements.

---

## 📖 Project Overview

Blood availability is a critical requirement during medical emergencies. Finding suitable blood donors quickly can be challenging and time-consuming.

The Blood Point Management System was developed to address this problem by creating a simple web application that stores donor information and allows users to search for matching donors efficiently.

This project demonstrates the implementation of database-driven web applications using PHP and MySQL.

---

## 🎯 Objectives

- Create a centralized donor database
- Allow donor registration through an online form
- Provide login functionality for registered users
- Enable searching donors by blood group
- Store and manage donor information securely
- Improve accessibility of donor information during emergencies

---

## ✨ Features

### Donor Registration
- New donor account creation
- Personal and medical information collection
- Blood group selection

### User Authentication
- Secure login system
- Credential verification

### Donor Search
- Search donors by blood group
- Quick retrieval of donor details

### Donor Information Management
- Store donor details in MySQL database
- Retrieve donor records dynamically

### Responsive User Interface
- Bootstrap-based design
- User-friendly forms and pages

---

## 🏗 System Architecture

```text
User
 │
 ▼
Web Interface (HTML, CSS, Bootstrap)
 │
 ▼
PHP Backend
 │
 ▼
MySQL Database
```

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| PHP | Backend Development |
| MySQL | Database Management |
| HTML5 | Structure |
| CSS3 | Styling |
| Bootstrap | Responsive UI |
| XAMPP | Local Development Environment |

---

## 📂 Project Structure

```text
blood-point-management-system/
│
├── Login.php
├── signup.php
├── details.php
├── filter.php
├── mini_db_conn.php
├── d_details.sql
├── Style.css
│
├── assets/
│   ├── css/
│   ├── images/
│   ├── fonts/
│   └── gallery/
│
└── Final Report.pdf
```

---

## 🗄 DataBase

The project uses a MySQL database named:

```sql
blood_point
```

Main table:

```sql
d_details
```

The table stores:

- Donor Name
- Parent Information
- Date of Birth
- Blood Group
- Contact Information
- Address Details
- Medical Information
- Login Credentials

---

## 🚀 Installation Guide

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/blood-point-management-system.git
```

### Step 2: Move Project

Copy the project folder into:

```text
xampp/htdocs/
```

### Step 3: Start XAMPP

Start:

- Apache
- MySQL

### Step 4: Create Database

Open phpMyAdmin and create:

```sql
blood_point
```

### Step 5: Import Database

Import:

```text
d_details.sql
```

### Step 6: Configure Database Connection

Update database credentials in:

```php
mini_db_conn.php
```

### Step 7: Run Project

Open browser:

```text
http://localhost/blood-point-management-system
```

---

## 📸 Modules Included

- Login Module
- Registration Module
- Blood Group Search Module
- Donor Listing Module
- Database Connectivity Module

---

## 🎓 Academic Purpose

This project was developed as a group mini-project for learning and demonstrating:

- Web Development Fundamentals
- Database Integration
- PHP Programming
- CRUD Operations
- Frontend and Backend Interaction

---

## 📚 Learning Outcomes

Through this project, the team gained experience in:

- PHP Development
- MySQL Database Design
- Authentication Systems
- Form Handling
- Database Connectivity
- Web Application Development
- Team Collaboration

---

## 🤝 Team Project

This repository represents a collaborative academic mini-project completed as part of coursework.

The project was developed for educational purposes to understand the practical implementation of web technologies and database-driven applications.

---

## ⭐ Future Improvements

- Admin Dashboard
- Password Encryption
- Email Verification
- Blood Request Module
- Appointment Scheduling
- Donor Availability Tracking
- Mobile Responsive Enhancements
- Advanced Search Filters

---

## 📄 License

This project is intended for educational and learning purposes.
