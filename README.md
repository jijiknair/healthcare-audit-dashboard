# Healthcare Audit Dashboard

## Overview
This project implements a **real-time monitoring dashboard** for healthcare compliance, integrating data from multiple sources and visualizing it with **Django**, **Power BI**, and **Chart.js**.

## Features
- **Real-Time Monitoring:** Live updates of healthcare compliance data.
- **Interactive Charts:** Visualizations using Chart.js for trend and KPI tracking.
- **Power BI Integration:** Embedded Power BI reports for advanced analytics.
- **User Management:** Role-based access to dashboards and reports.

## Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript, Chart.js
- **Analytics:** Power BI
- **Database:** PostgreSQL

## Project Structure

healthcare-audit-dashboard/
│
├── dashboard/               # Main Django app for views, models, and API endpoints
│   ├── migrations/           # Database migrations
│   ├── static/               # CSS, JavaScript, images
│   │   ├── css/
│   │   ├── js/
│   │   └── images/
│   ├── templates/            # HTML templates
│   │   └── dashboard/
│   ├── admin.py               # Admin panel configuration
│   ├── apps.py                # App configuration
│   ├── models.py              # Database models
│   ├── urls.py                # URL routing for the dashboard
│   ├── views.py               # View functions and API endpoints
│   └── tests.py               # Unit tests
│
├── healthcare_audit/         # Django project configuration (settings, URLs, WSGI)
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── requirements.txt          # Python dependencies
├── manage.py                  # Django management script
└── README.md                  # Project documentation
