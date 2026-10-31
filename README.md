# Sand Aggregates

## About the Project

Sand Aggregates is a modern construction material supplier website developed using Python and Django. It is designed for sand suppliers, aggregate dealers, and construction material businesses.

The platform allows customers to browse construction materials, view product details and pricing, submit order requests, request quotations, and contact suppliers through WhatsApp.

The website provides a simple and responsive interface for managing construction material enquiries and orders.

## Features

- Modern and responsive business website.
- Product catalog with category-wise listings.
- Individual product detail pages.
- Product specifications and pricing information.
- WhatsApp-based enquiry functionality.
- Order request form with quantity and total calculation.
- Custom enquiry and quotation request forms.
- Admin dashboard for managing products, orders, and enquiries.
- Configurable business details, including phone number, address, and WhatsApp link.
- Environment variable support.
- WhiteNoise support for static file hosting.

## Product Categories

The platform supports the following construction materials:

- River Sand
- Construction Sand
- M-Sand
- Crushed Stone Aggregates
- Road Sub-base / GSB
- Bulk Construction Materials

## Technology Stack

- **Backend:** Python, Django 4.2+
- **Frontend:** HTML5, CSS3, JavaScript
- **Database:** SQLite
- **UI Styling:** Bootstrap Utility Classes
- **Image Processing:** Pillow
- **Static File Management:** WhiteNoise
- **Version Control:** Git and GitHub

## Project Structure

```text
Sand-Aggregates/
│
├── index.html
├── css/
├── js/
├── assets/
├── images/
├── netlify.toml
├── vercel.json
├── DEPLOYMENT_GUIDE.md
│
├── sand_aggregates/
│   ├── manage.py
│   ├── requirements.txt
│   ├── .env.example
│   ├── .env
│   ├── db.sqlite3
│   ├── pythonanywhere_wsgi.py
│   │
│   ├── sand_aggregates/
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── asgi.py
│   │
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
│   │
│   ├── static/
│   ├── templates/
│   ├── media/
│   └── staticfiles/
│
└── README.md
```

## Installation and Setup

### Prerequisites

Make sure the following software is installed:

- Python 3.10 or above
- Git
- pip (Python Package Manager)

### 1. Clone the Repository

```bash
git clone https://github.com/jeelpatel3807/Sand-Aggregates.git
```

### 2. Navigate to the Project Directory

```bash
cd Sand-Aggregates
```

Navigate to the Django project directory:

```bash
cd sand_aggregates
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Apply Database Migrations

```bash
python manage.py migrate
```

### 7. Load Sample Data (Optional)

```bash
python manage.py seed_data
```

### 8. Create an Admin Account

```bash
python manage.py createsuperuser
```

Follow the instructions to create your administrator account.

### 9. Run the Development Server

```bash
python manage.py runserver
```

### 10. Access the Application

Open the following URLs in your browser:

**Website:**

http://127.0.0.1:8000/

**Products:**

http://127.0.0.1:8000/products/

**Admin Dashboard:**

http://127.0.0.1:8000/admin/
```
