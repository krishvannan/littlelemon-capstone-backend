# Little Lemon capstone Backend 

## 📁 Project Structure

```text
littlelemon/
├── manage.py              # Django management script
├── db.sqlite3             # SQLite database
├── littlelemon/
│   ├── settings.py        # Project settings
│   ├── urls.py            # Main URL routing
│   └── wsgi.py            # WSGI configuration
├── restaurant/
│   ├── models.py          # Menu and Booking models
│   ├── views.py           # API views
│   ├── serializers.py    # DRF serializers
│   ├── urls.py            # App URL routing
│   └── admin.py           # Admin configuration
├── static/                # Static files
├── templates/
│   └── index.html         # Homepage
└── tests/
    ├── test_models.py
    └── test_views.py


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

