# 📚 Books CRUD Application (Django)

This is a **Django CRUD (Create, Read, Update, Delete) application** that allows users to manage books.  
Users can add new books, view a list of books, see book details, update book information, and delete books.

This project is designed for **beginners learning Django** and demonstrates core Django concepts such as models, views, templates, forms, static files, and database migrations.

---

## 🚀 Features

- Create new book records
- View a list of all books
- View details of a single book
- Edit existing book information
- Delete books with confirmation
- Clean and professional UI using CSS
- Uses Django template inheritance
- SQLite database (default Django database)

---

## 🛠 Technologies Used

- Python
- Django
- HTML (Django Templates)
- CSS
- SQLite (Database)

---

## 📂 Project Structure

```bash

Books-CRUD/
│
├── Books_CRUD/ # Project settings
│ ├── settings.py
│ ├── urls.py
│ └── ...
│
├── books/ # Main app
│ ├── models.py # Database models
│ ├── views.py # View logic
│ ├── urls.py # App URLs
│ ├── forms.py # Django forms
│ ├── templates/
│ │ └── books/
│ │ ├── base.html
│ │ ├── book_list.html
│ │ ├── book_detail.html
│ │ ├── book_form.html
│ │ └── book_confirm_delete.html
│ └── static/
│ └── books/
│ └── style.css
│
├── db.sqlite3 # Database
├── manage.py
└── README.md

```
---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Yezdani01/Book-Management
cd Books-CRUD
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
pip install django
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

```

### Author Hamzaa