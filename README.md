University Event Management System (EMS) README
Your SGRR University EMS is a Django-based web application designed to streamline event organization, registration, and management for university activities.�� It centralizes event details like titles, types, dates, venues, classes, and audience expectations, while handling roles for participants, judges, hosts, guests, and winners.�
Key Features
Event Creation and Listing: Admins add and display events on the homepage with full details.�
Role-Based Management: Track attendance, registrations, and winners for different user roles.�
User Views: Normal users browse events; admins control all data and updates.�
Centralized Dashboard: Reduces manual paperwork by digitizing event tracking.�
Tech Stack
Backend: Django framework for web development and admin panel.�
Database: SQLite3 – lightweight, serverless, ideal for development and small-scale use.��
Frontend: HTML templates with Django views; runs locally on http://127.0.0.1:8000.�
Quick Setup
Clone the project and install dependencies: pip install django.
Run migrations: python manage.py makemigrations && python manage.py migrate.
Create superuser: python manage.py createsuperuser.
Start server: python manage.py runserver.
Access admin at /admin/ to add events and users.�
Usage
Admins log in to create events and manage records.
Users view events and details without login.
Tracks everything from registration to results in one place.�
Why SQLite3?
SQLite3 suits this project as it's Django's default, requires no extra setup, and handles college-level data efficiently – unlike MySQL for large production apps.��
This system improves university event efficiency; consider adding notifications or mobile support next.
