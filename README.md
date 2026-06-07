# Django Basics

A repository documenting my journey of learning Django, Python's high-level web framework.

## Topics Covered

- Django Introduction
- Django Project Structure
- Virtual Environments
- Django Apps
- URL Routing
- Views
- Templates
- Static Files
- Models
- Database Migrations
- Admin Panel
- Forms
- CRUD Operations
- Authentication & Authorization
- Class-Based Views
- Django ORM
- Deployment Basics

## Tech Stack

- Python
- Django
- SQLite
- HTML
- CSS

## Setup

### Clone the Repository

```bash
git clone <repository-url>
cd django-basics
```

### Create Virtual Environment

```bash
python3 -m venv env
```

### Activate Virtual Environment

#### macOS/Linux

```bash
source env/bin/activate
```

#### Windows

```bash
env\Scripts\activate
```

### Install Dependencies

```bash
pip install django
```

### Run the Development Server

```bash
python manage.py runserver
```

Open:

```
http://127.0.0.1:8000/
```

## Project Structure

```text
django-basics/
│
├── manage.py
├── db.sqlite3
├── project/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   ├── wsgi.py
│   └── __init__.py
│
├── employees/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
└── README.md
```

## Goals

- Learn Django fundamentals.
- Build projects using Django.
- Understand backend development.
- Practice Django best practices.
- Track progress publicly on GitHub.

## Progress

- [x] Environment Setup
- [x] Django Installation
- [ ] URL Routing
- [ ] Views
- [ ] Templates
- [ ] Models
- [ ] Forms
- [ ] Authentication
- [ ] Deployment

## Notes

This repository is for learning and practice purposes. Code, notes, and mini-projects will be added as I progress through Django.

---

If you're learning Django too, feel free to explore the repository.