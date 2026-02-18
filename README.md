# django-ecommerce-application
# 🛒 Django E-Commerce Web Application

This is a Django-based E-Commerce web application built using Python and Django.

The project is inspired by the tutorial series:
"Creating an E-Commerce Web Application with Django and Tailwind CSS" by Code Snippets.

🔗 Tutorial Reference:  
https://codesnnippets.com/creating-an-e-commerce-web-application-with-django-and-tailwind-css-part-1/

---

## 🚀 Features

- User Authentication (Login / Register)
- Product Listing
- Product Detail View
- Add to Cart Functionality
- Order Management
- Admin Dashboard
- Responsive Design
- Media & Static File Handling

---

## 🛠️ Tech Stack

- Python 3
- Django 3.2
- SQLite (Development)
- Tailwind CSS
- Gunicorn (Production Server)
- Git & GitHub

---

## 📱 Application Preview

![Mobile View 1](https://user-images.githubusercontent.com/71964085/200704498-de5f43e0-0bf8-4278-91a9-8a9b47a6bf65.png)
![Mobile View 2](https://user-images.githubusercontent.com/71964085/200704523-44619485-eeb1-4ac0-a636-9155b686a076.png)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/iam-manaligawade/django-ecommerce-cloud-ready.git
cd django-ecommerce-cloud-ready
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/Scripts/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations

```bash
python manage.py migrate
```

### 5️⃣ Run Development Server

```bash
python manage.py runserver
```

Open in browser:
```
http://127.0.0.1:8000/
```

---

## ☁️ Deployment Ready

This project is configured for production deployment using:

- DEBUG = False configuration
- ALLOWED_HOSTS setup
- Gunicorn WSGI server
- Static file collection

It is ready for deployment on AWS EC2.

---

## 📚 Learning Outcome

Through this project, I gained practical experience in:

- Django Project Structure
- Database Migrations
- Authentication Systems
- Virtual Environment Management
- Debugging Version Conflicts
- Git & GitHub Workflow
- Preparing Django Applications for Cloud Deployment

---

## 👩‍💻 Author

Manali Gawade  
Cloud & DevOps Enthusiast
