# Little Lemon capstone Backend 

## 📁 Project Structure

littlelemon/
├── manage.py                   # Django management script
├── db.sqlite3                  # SQLite database
├── littlelemon/               # Project configuration
│   ├── settings.py            # Project settings
│   ├── urls.py                # Main URL routing
│   └── wsgi.py                # WSGI configuration
├── restaurant/                # Restaurant app
│   ├── models.py              # Menu and Booking models
│   ├── views.py               # API views
│   ├── serializers.py         # DRF serializers
│   ├── urls.py                # App URL routing
│   ├── admin.py               # Admin configuration
│   └── static/                # Static files (images, CSS)
├── templates/                 # HTML templates
│   └── index.html             # Homepage
└── tests/                     # Unit tests
    ├── test_models.py         # Model tests
    └── test_views.py          # View tests


## 🚀 Features

- User registration and authentication (Token-based)
- Menu item CRUD operations
- Table booking management
- Role-based access control (Admin vs Regular users)
- Django admin panel
- Static templates support
- Unit testing for API endpoints

---

## 🧠 Tech Stack

- **Python**
- **Django**
- **Django REST Framework**
- **Djoser** (Authentication)
- **SQLite** (Development database)
- **HTML / CSS / JavaScript**
- **Django Test Framework**

