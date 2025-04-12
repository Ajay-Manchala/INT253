# 🏥 Hospital Management System - Django Project

This is a **Hospital Management System** built using **Django (Python Web Framework)**. The system allows hospital staff, doctors, and patients to manage appointments, records, and workflows digitally.

## 🚀 Features

- Admin panel for hospital management
- Doctor login and patient appointments
- Patient record management
- Prescription management
- Secure user authentication
- Responsive UI

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default, can switch to PostgreSQL/MySQL)
- **Authentication**: Django built-in user auth

## 📁 Project Structure

hospital_management/ ├── hospital/ # Core application │ ├── migrations/ │ ├── templates/ │ ├── static/ │ ├── views.py │ ├── models.py │ ├── urls.py │ └── ... ├── hospital_management/ # Project settings │ ├── settings.py │ ├── urls.py │ └── ... ├── db.sqlite3 └── manage.py


## ⚙️ Setup Instructions

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/hospital-management-system-django.git
cd hospital-management-system-django
2. Requirements 
pip install -r requirements.txt
3. Migrations
python manage.py makemigrations
python manage.py migrate
4. Create Super User
python manage.py createsuperuser


Access App

Go to http://127.0.0.1:8000/ in your browser

Use superuser credentials to login to the admin panel at http://127.0.0.1:8000/admin/

📸 Screenshots
(Add screenshots of your home page, login, and dashboard here)

🙋 Author
Developed by Ajay Manchala

Email: ajaymanchala1208@gmail.com

