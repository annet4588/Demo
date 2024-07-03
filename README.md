# Django Todo App

A simple Todo application built with Django.

## Features

- Add, update, and delete todos
- Mark todos as completed or not completed
- Responsive design using Bootstrap

## Requirements

- Python 3.6+
- Django 3.0+
- Bootstrap 4.3.1 (included via CDN)

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/demo.git
    cd django-todo
    ```

2. **Create and activate a virtual environment:**

    On Windows:
    ```sh
    python -m venv .env
    .env\Scripts\activate
    ```

    On macOS and Linux:
    ```sh
    python3 -m venv .env
    source .env/bin/activate
    ```

3. **Install the dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Run migrations:**
    ```sh
    python manage.py migrate
    ```

5. **Create a superuser:**
    ```sh
    python manage.py createsuperuser
    ```

6. **Run the development server:**
    ```sh
    python manage.py runserver
    ```

7. **Access the app:**
    Open your web browser and go to `http://127.0.0.1:8000/`

## Project Structure
demo/
├── demo/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── myapp/
│ ├── migrations/
│ ├── static/
│ ├── templates/
│ │ ├── base.html
│ │ └── home.html
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── tests.py
│ ├── urls.py
│ └── views.py
├── manage.py
