# Golden Crust Bakery – Django Final Project

A multi-page bakery website built with **Django Templates** for the DMMMSU-NLUC College of Information System Final Project (Django Templates & GitHub).

## Project Overview

**Golden Crust Bakery** is a fictional neighborhood bakery in Bacnotan, La Union.  
The website showcases the bakery’s story, daily menu, gallery, and contact information using clean, responsive design and proper Django template practices.

**Problem it solves:** Local bakeries often lack a simple online presence where customers can view products, learn about the shop, and find contact details.

**Target users:** DMMMSU students, families, and residents of North La Union who want fresh bread and pastries.

## Features

- 5 complete pages: Home, About, Menu, Gallery, Contact
- Template inheritance with `base.html` and `{% block %}` / `{% extends %}`
- Reusable navbar and footer via `{% include %}`
- Named URL patterns with `{% url %}` tags (no hard-coded paths)
- Static files (CSS) loaded with `{% load static %}` and `{% static %}`
- Clean, mobile-friendly design with bakery-themed colors

## Tech Stack

- Python 3.x
- Django 4.2+
- HTML5 / CSS3 (no frontend frameworks)
- Git & GitHub

## How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/clydedizon02-coder/GoldenCrust_Bakery_Django_Project.git
cd GoldenCrust_Bakery_Django_Project

# 2. Create and activate virtual environment
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Start the development server
python manage.py runserver
```

Open http://127.0.0.1:8000/ in your browser.

## Project Structure

```
GoldenCrust_Bakery_Django_Project/
├── bakery_project/          # Project settings
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── main/                    # Main app
│   ├── templates/main/
│   ├── static/main/css/
│   ├── views.py
│   └── urls.py
├── manage.py
├── requirements.txt
└── README.md
```

## Pages

| Page    | URL          | Description                    |
|---------|--------------|--------------------------------|
| Home    | `/`          | Welcome + featured items       |
| About   | `/about/`    | Bakery story & values          |
| Menu    | `/menu/`     | Daily bread & pastry offerings |
| Gallery | `/gallery/`  | Photo showcase                 |
| Contact | `/contact/`  | Location, hours, contact form  |


DMMMSU-NLUC – College of Information System
