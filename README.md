# 📚 Book Store API – Django REST Framework

The **Book Store API** is a backend RESTful service built with **Django REST Framework**.  
It provides features for managing books, categories, users, orders, and authentication.  
This project is designed as a clean, scalable API structure suitable for e-commerce or learning purposes.

---

## 🚀 Features

### 📘 **Books**
- Add, view, update, delete books  
- Search & filter by title, author, category  
- Pagination for large lists  

### 🏷 **Categories**
- Create and manage book categories  
- Filter books by category  

### 👤 **Users**
- User registration & login  
- JWT authentication  
- Profile access  

### 🛒 **Orders**
- Create orders  
- Add/remove books from cart  
- Order history per user  

### 🔐 **Authentication**
- JWT Access & Refresh tokens  
- Protected routes for orders  
- Permissions for admin vs normal users  

---

## 🛠️ Tech Stack

**Backend:**  
- Python  
- Django  
- Django REST Framework  

**Database:**  
- PostgreSQL or SQLite  

**Auth:**  
- JWT (SimpleJWT)

**Tools:**  
- Postman  
- Docker (optional)

---

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/SAI909099/book_shop_drf.git
cd book_shop_drf

2️⃣ Create virtual environment
python -m venv env
source env/bin/activate   # Linux / Mac
env\Scripts\activate      # Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Apply migrations
python manage.py migrate

5️⃣ Run development server
python manage.py runserver

🔑 Authentication (JWT)
Login
POST /api/token/

Refresh
POST /api/token/refresh/


Usage:

Authorization: Bearer <access_token>
```

👨‍💻 Author
Abdulazizxon Sulaymonov
Python Backend Developer

📧 Email: sulaymonovabdulaziz1@gmail.com

GitHub: https://github.com/SAI909099

