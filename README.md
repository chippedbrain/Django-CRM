# Django CRM Tutorial Project

This project is a simple Customer Relationship Management (CRM) system built with Django, PostgreSQL, and Bootstrap. It started as a learning project and has evolved over time with added features and improvements.

## Features

- User authentication: Users can log in to the system.
- Customer management: Users can create, modify, and delete customer records in the database.
- Template system: Utilizes Django's template system for a dynamic and responsive user interface.

## Tech Stack

- **Django**: Python Web framework known for rapid development and clean design.
- **PostgreSQL**: Robust open-source relational database system.
- **Bootstrap**: Widely-used CSS framework for creating responsive and mobile-friendly web interfaces.1

## Getting Started

To get a local copy up and running, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/yourusername/yourrepository.git
```

2. Change into the Project directory:

```bash
cd your_repository
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Set up your database in settings.py:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your_database_name',
        'USER': 'your_username',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
```

5. Run the migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

6. Start the development server:
```bash
python manage.py runserver
```

Now you can access the application at http://localhost:8000.
