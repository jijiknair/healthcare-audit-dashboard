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

### **Folder/Component Details**

- **dashboard/** – Core application handling the healthcare compliance dashboard logic, views, and templates.
- **static/** – Contains all static front-end assets (CSS, JavaScript, images).
- **templates/** – Holds the HTML templates used to render the pages.
- **migrations/** – Database migration files for keeping schema changes in sync.
- **models.py** – Defines the database structure (tables, fields, relationships).
- **views.py** – Controls what data is shown and which templates are used.
- **urls.py** – Maps URLs to the corresponding views.
- **settings.py** – Project-wide configuration (databases, installed apps, middleware).
- **requirements.txt** – Lists all required Python packages for easy installation.

