# Sand Aggregates Management

A production-ready Django-based business platform for sand, aggregates, and construction material suppliers. This project transforms a static business website into a dynamic ordering and management system with catalog browsing, direct WhatsApp-based order flow, enquiry handling, and operational admin dashboard features.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.10+" />
  <img src="https://img.shields.io/badge/Django-4.2-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django 4.2" />
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Active" />
</p>

## Overview

This application is designed for companies dealing in:

- River sand
- M-Sand
- Construction sand
- Crushed stone aggregates
- Road sub-base / GSB
- Bulk material supply for construction projects

It combines a premium industrial web design with a working business backend that supports leads, product catalog management, customer orders, and admin operations.

---

## Key Features

- Dynamic homepage with company branding and product highlights
- Product catalog with category-wise listing
- Material detail pages with specifications
- WhatsApp-enabled inquiry and order follow-up flow
- Enquiry/quotation submission system
- Admin dashboard for order and enquiry tracking
- Product availability and featured product controls
- Site settings management for phone, address, social links, and business data
- Environment-variable-based configuration for deployment
- WhiteNoise support for production static file serving

---

## Tech Stack

- Python
- Django 4.2+
- SQLite (default development database)
- HTML5
- CSS3
- JavaScript
- Bootstrap utility classes
- Pillow for image handling
- WhiteNoise for static files

---

## Project Structure

```text
Sand_aggregates/
├── index.html
├── css/
├── js/
├── assets/
├── images/
├── netlify.toml
├── vercel.json
├── DEPLOYMENT_GUIDE.md
├── sand_aggregates/
│   ├── manage.py
│   ├── requirements.txt
│   ├── .env.example
│   ├── .env
│   ├── db.sqlite3
│   ├── pythonanywhere_wsgi.py
│   ├── README.md
│   ├── sand_aggregates/
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── asgi.py
│   ├── website/
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── forms.py
│   │   ├── models.py
│   │   ├── tests.py
│   │   ├── urls.py
│   │   ├── views.py
│   │   ├── context_processors.py
│   │   └── management/
│   ├── static/
│   ├── templates/
│   ├── media/
│   └── staticfiles/
└── README.md


If you want, I can also give you:
- a shorter GitHub version,
- a more premium portfolio-style version,
- or a version with badges and a hero section styled for GitHub.
