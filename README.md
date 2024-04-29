# Django CRM Tutorial Project

This project is a simple Customer Relationship Management (CRM) system built with Django, PostgreSQL, and Bootstrap. It was created following a tutorial for learning purposes.

## Features

- User authentication: Users can log in to the system.
- Customer management: Users can create, modify, and delete customer records in the database.

## Tech Stack

- **Django**: A high-level Python Web framework that encourages rapid development and clean, pragmatic design.
- **PostgreSQL**: A powerful, open-source object-relational database system.
- **Bootstrap**: A free and open-source CSS framework directed at responsive, mobile-first front-end web development.

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
