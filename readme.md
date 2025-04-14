
# 📇 Smart Contact Manager

A powerful, secure, and user-friendly **Contact Management Web Application** built using **Spring Boot**, **Thymeleaf**, **Tailwind CSS**, and **MySQL**. This project helps users efficiently manage their personal or professional contacts with features like OAuth2 login, image uploads, favorites, and more.
---

## 🔥 Features

✅ User Registration and Login  
✅ Email & Password based login  
✅ **OAuth2 Login** (Google, GitHub)  
✅ **Email Verification** using token-based link  
✅ **Add, Edit, Delete Contacts**  
✅ **Mark Contact as Favorite**  
✅ Contact details include:
- LinkedIn & Facebook URLs
- Address, Description, and Profile Picture  
✅ Upload profile images to **Cloudinary**  
✅ Pagination & Search contacts  
✅ Profile Dashboard  
✅ Fully responsive using **Tailwind CSS**

---

## 🚀 Tech Stack

| Layer             | Technology Used                        |
|------------------|----------------------------------------|
| Language          | Java 17                                |
| Backend Framework | Spring Boot 3, Spring MVC              |
| Security          | Spring Security, OAuth2                |
| Frontend          | Thymeleaf, Tailwind CSS, HTML, JS      |
| Database          | MySQL                                  |
| Build Tool        | Maven                                  |
| Hosting (Media)   | Cloudinary (Image uploads)             |

---

## 🔐 Authentication Features

- **Manual Sign-Up** with Email + Password
- **OAuth2** via GitHub and Google
- **Email Verification** using verification token link
- Passwords are stored using **BCrypt**

---

## 🛠️ Installation Guide

### 📦 Prerequisites
- Java 17+
- MySQL Server
- Maven
- Git

### 💻 Setup

```bash
# Step 1: Clone the repository
git clone https://github.com/ketan0801/SCM.git
cd SCM

# Step 2: Setup database
# Create a database named scm2 in MySQL

# Step 3: Configure application.properties
# Update src/main/resources/application.properties with your DB and Cloudinary credentials

# Step 4: Build the project
mvn clean install

# Step 5: Run the project
mvn spring-boot:run
