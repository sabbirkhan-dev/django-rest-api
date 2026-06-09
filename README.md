# Django REST API

A RESTful API built with Django and Django REST Framework (DRF) for learning and practicing backend development concepts.

## Features

* Django REST Framework (DRF)
* RESTful API Architecture
* CRUD Operations
* JSON Responses
* API Routing
* Environment Variable Configuration
* Git & GitHub Integration

## Technologies Used

* Python
* Django
* Django REST Framework
* SQLite
* Git
* GitHub

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/django-rest-api.git
cd django-rest-api
```

Create and activate a virtual environment:

```bash
python -m venv venv
```

Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file and add:

```env
SECRET_KEY=your_secret_key
DEBUG=True
```

Apply migrations:

```bash
python manage.py migrate
```

Run the development server:

```bash
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```

## Project Structure

```text
django-rest-api/
│
├── core/
├── books/
├── manage.py
├── requirements.txt
├── .env
└── README.md
```

## API Testing

You can test the API using:

* Insomnia
* Postman
* Browser
* cURL

## Author

Sabbir
Python Developer
