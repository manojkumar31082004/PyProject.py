# Job Portal Web Application

This is a Flask-based web application that allows users to register, log in, and apply for jobs. Employers can post new job listings and manage job applications.

## Features

- User Registration and Login
- Employer Job Posting
- Job Listings Page
- Job Application with Success Confirmation
- Admin Dashboard Panel

## Project Structure

Job_Portal/
├── app.py # Main application logic
├── models.py # Database models using SQLAlchemy
├── requirements.txt # Python dependencies
├── templates/ # HTML templates
│ ├── admin_panel.html
│ ├── apply_success.html
│ ├── dashboard.html
│ ├── index.html
│ ├── job_list.html
│ ├── login.html
│ ├── post_job.html
│ └── register.html
└── pycache/ # Python cache files (can be ignored)

## Installation

1. **Clone or extract the repository**:
   ```bash
   cd Job_Portal
2.**Dependencies**:
  ```bash
   pip install -r requirements.txt

## Run
```bash
   python app.py
