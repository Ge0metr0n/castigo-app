# 🎯 Castigo App

A full-stack web application that allows users to maintain a personal list of businesses they want to boycott for a specified period.

## 🛠️ Tech Stack

**Frontend:**

- React 18
- Vite
- TailwindCSS
- React Router
- Leaflet (for maps)
- Axios

**Backend:**

- Django 5.0
- Django REST Framework
- PostgreSQL
- JWT Authentication

## 📋 Features (Planned)

- ✅ User registration and authentication
- ✅ Add businesses to punishment list
- ✅ Set punishment duration (1-12 months or permanent)
- ✅ View punishments on interactive map
- ✅ Track punishment expiry dates
- ✅ Search and find places via OpenStreetMap
- ✅ Filter by status (active/completed)

## 🚀 Installation & Setup

### Prerequisites

- Python 3.11+
- Node.js 20+
- PostgreSQL 14+

### Backend Setup

1. Create virtual environment: `python -m venv venv`
2. Activate: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Mac/Linux)
3. Install dependencies: `pip install -r requirements.txt`
4. Create PostgreSQL database named `castigo_db`
5. Copy `.env.example` to `.env` and configure database credentials
6. Run migrations: `python manage.py migrate`
7. Create superuser: `python manage.py createsuperuser`
8. Run server: `python manage.py runserver`

### Frontend Setup

1. Navigate to frontend: `cd frontend`
2. Install dependencies: `npm install`
3. Create `.env` file with API URL
4. Run dev server: `npm run dev`

## 📝 Development Status

🚧 Currently in development - Module 1 Complete!

## 👨‍💻 Author

Built as part of high school work experience programme.

## 📄 License

This project is for educational purposes.
