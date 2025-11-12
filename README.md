# Healthcare Appointment Booking


## Overview
A simple MVC-based appointment booking system for clinics and doctors. Built with Flask, SQLAlchemy, and Jinja2 templates.


## Features
- User registration & login (Patient/Doctor/Admin)
- Doctor timeslot management
- Patient appointment booking & cancellation
- Role-based dashboards


## Setup (development)
1. python -m venv venv
2. source venv/bin/activate # or venv\Scripts\activate on Windows
3. pip install -r requirements.txt
4. cp .env.example .env and set DATABASE_URL
5. flask db upgrade # if using migrations
6. flask run


## Tests
Run `pytest` to execute unit tests.
