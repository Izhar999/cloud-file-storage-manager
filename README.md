# ☁️ Cloud File Storage Manager (Google Drive Clone)

## 🚀 Project Overview
Cloud File Storage Manager is a backend-driven cloud storage system where users can securely upload, manage, and share files using AWS S3 as storage and PostgreSQL as the database.

This project demonstrates production-level backend architecture including authentication, authorization, and role-based access control.

---

## 🛠️ Tech Stack

### Backend
- Django
- Django REST Framework
- PostgreSQL
- JWT Authentication (SimpleJWT)

### Cloud
- AWS S3 (Upcoming Integration)

### Tools
- Postman (API Testing)
- Git & GitHub

---

## 🔐 Authentication & Authorization

- Custom email-based user model
- JWT authentication (Access + Refresh tokens)
- Protected APIs using Bearer token
- Role-Based Access Control (Admin / User)
- Custom permission classes
- Admin-only endpoints

---

## 📁 File System Design

### File Model Fields:
- Owner (ForeignKey to User)
- File Name
- File Size
- S3 Key
- S3 URL
- Public / Private toggle
- Upload timestamp

---

## 🏗️ Architecture

Client (React - upcoming)
        ↓
Django REST API
        ↓
PostgreSQL (metadata)
        ↓
AWS S3 (file storage)

---

## 📌 Current Status

✅ Backend authentication system completed  
✅ Role-based access control implemented  
✅ Admin-restricted APIs working  
✅ File database structure created  
🚧 File upload APIs in progress  
🚧 AWS S3 integration upcoming  

---

## 🎯 Why This Project?

This project demonstrates:

- Real-world backend architecture
- Secure stateless authentication
- Role-based permission systems
- Cloud storage integration
- Industry-level REST API design

---

## 👨‍💻 Author

Izharul Hassan


Project under active development.