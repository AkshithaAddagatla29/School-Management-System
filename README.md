# School Management System

## Description
The **School Management System** is a powerful and efficient tool designed to help educational institutions manage students, teachers, courses, attendance, and more. It simplifies administrative tasks and enhances the overall learning experience.

## Features
- **User Authentication**: Secure login for admins, teachers, and students.
- **Student Management**: Add, update, and track student records.
- **Teacher Management**: Manage teacher profiles, schedules, and assignments.
- **Course Management**: Assign courses to teachers and students.
- **Attendance Tracking**: Record and monitor student attendance.
- **Examination Module**: Conduct and manage exams with grading automation.
- **Fee Management**: Track student fee payments and generate invoices.
- **Notifications & Reports**: Send notifications and generate performance reports.

## Tech Stack
- **Backend:**
  - Python 3
  - Django
  - Django Rest Framework
  - PostgreSQL / MySQL (Database)
- **Frontend:**
  - HTML
  - CSS
  - JavaScript
  - Bootstrap

## Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/school-management-system.git
2. **Navigate to the project directory:**
   ```bash
  cd school_management_system
  
3. **Create a virtual environment:**
   ```bash
    python -m venv venv

3. **Activate the virtual environment:**
   ```bash
  source venv/bin/activate  # For Linux/Mac
  venv\Scripts\activate  # For Windows

4. **Install dependencies:**
   ```bash
  pip install -r requirements.txt
  
5. **Set up the database:**
   ```bash
  python manage.py migrate

6. **Create a superuser account:**
   ```bash
  python manage.py createsuperuser
   
9. **Run the application:**
   ```bash
   python manage.py runserver
