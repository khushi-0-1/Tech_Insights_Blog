# Tech Insights Blog Project

**Overview**  
This project is a full-stack blogging platform built using the Django web framework. It allows users to explore blog posts, read articles by category, and interact through a comment system. The platform also includes an administrative dashboard where authorized users can manage posts, categories, and users efficiently.

---

## Features

- Project structure & real-world folder layout
- User authentication (register, login, logout)
- Blog post management with categories
- Create, read, update, and delete (CRUD) operations for posts
- Comment system for authenticated users
- Featured posts and recent articles section
- Search functionality for blog posts
- Image upload support for blog posts
- Admin dashboard for managing users, posts, and categories
- Role-based access using Django authentication and permissions

---

## Tech Stack
- Backend: Django (Python)
- Frontend: HTML, CSS, Bootstrap
- Database: SQLite (for development)
- Authentication: Django built-in authentication system

## Installation
### Clone the repository and install dependencies:
```bash
git clone <repository-url>
```
```bash
cd blogging-system 
```
```bash
python -m venv venv
```
```bash
venv\Scripts\activate 
```
```bash
pip install -r requirements.txt
```
### Run the development server:
```bash
python manage.py migrate 
```
```bash
python manage.py runserver
```
### Open in browser:
http://127.0.0.1:8000


