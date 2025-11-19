# 📚 Online Library Management System

[![Python](https://img.shields.io/badge/python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/) 
[![Django](https://img.shields.io/badge/django-4.x-green?logo=django&logoColor=white)](https://www.djangoproject.com/) 
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![SQLite](https://img.shields.io/badge/SQLite-3.x-orange?logo=sqlite&logoColor=white)](https://www.sqlite.org/index.html)  

A full-featured **To-Do List web application** built with **Python** and **Django**. Manage your tasks in a modern, responsive interface with secure user authentication.

---

## 🌟 Key Features

- 🔐 **User Authentication**: Register, log in, and manage your account securely.  
- ✏️ **CRUD Functionality**: Create, view, update, and delete books by admin.  
- 📚 **Book Management (Admin)**: Admins can perform full CRUD operations (Create, Read, Update, Delete) on books.
- 💬 **Review & Feedback**: Authenticated users can post comments and reviews under specific books.
- 🔎 **Book Browsing**: View a list of available books with detailed descriptions.
- 📱 **Responsive Design**: Works smoothly on mobile, tablet, and desktop.  

---

## 🛠️ Technology Stack

- **Backend:** Python, Django  
- **Frontend:** HTML, CSS  
- **Database:** SQLite3 (default, configurable)  
- **Version Control:** Git  

---

## 📂 Project Structure
The project is organized into a main Django project directory (`LMS`) and a primary application (`myLib`).
```csharp
├── LMS/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py             # Main Django project directory
│   ├── wsgi.py
│   └── urls.py
├── media/
│   ├── book_covers/
├── myLib/                     # The main application for handling logics
│   ├── migrations/
│   ├── admin.py
│   ├── forms.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── templates/                # Global templates
│   ├── booksf/
│   │   ├── book_detail.html  # Book-related templates
│   │   ├── book_form.html
│   │   └── book_list.html
│   ├── users/                
│   │   ├── login.html
│   │   ├── pass_change.html
│   │   ├── profile.html
│   │   ├── signup.html
│   │   └── update_profile.html
│   └── base.html
└── manage.py                 # Django's command-line utility
```
---

<!-- ## 🌐 Live Project

You can try out the deployed app here:  
[**To-Do Web App**](https://todo-web-app-kg5f.onrender.com)   -->

---

## 🚀 Local Setup
**1. Clone the repo**  
```bash
git clone https://github.com/turjo25/Online_Library_Django.git
cd LMS/
```
**2. Create a virtual environment**
```bash
python -m venv env
source env/bin/activate   # Linux / Mac
env\Scripts\activate      # Windows
```
**3. Apply migrations**
```bash
python manage.py migrate
```
**4. Create a superuser**
```bash
python manage.py createsuperuser
```
**5. Run the development server**
```bash
python manage.py runserver
```
>Open `http://127.0.0.1:8000` in your browser.
---
## 📝 Usage

For General Users:

1. **Register / Log In**  
   - Create a new account or log in with an existing one.  
   - Secure authentication ensures your tasks are private.

2. **View Profile**  
   - Access your profile to see your username, email, and basic account information.  
   - Provides an overview of your account before making any changes.

3. **My Profile**
   - Access your personal profile page by clicking on the **My Profile** button in the navigation bar.
   - My profile page displays your current username and email.  
   - Here your can Update your username, email, or password.  

4. **Book List**  
   - Browse through the list of available books.  

5. **View Details**  
    - Click on **View Details** to view detailed information, including title, author, description, and reviews.

6. **Search Books**  
   - Search books by **genre**: Fiction, Non-Fiction, Mystery, etc.
   - Search books by **name** or **author** using the search bar at the top.

7. **Add Comment**  
   - Click on a book to view its details and add your comments or reviews.

8. **Responsive Design**  
   - Use on any device: desktop, tablet, or mobile.  


---
## ⚡ Future Enhancements

- 📖 **Borrowing System**: Allow users to "borrow" books and track due dates.

- ⭐ **Star Ratings**: Add a visual rating system alongside comments.

- 🔔 **Notifications**: Implement in-app notifications for new comments or book additions.

- 📧 **Email Notifications**: Notify users when a new book is added or a request is approved.

## 🛡️ License
MIT License © 2025 Turjo





