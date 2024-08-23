# Django REST API with Swagger and ReDoc Documentation

This project demonstrates a basic Django RESTful API with integrated Swagger and ReDoc documentation.

## Project Overview

The project is designed to help developers understand how to create, document, and deploy a Django REST API. It includes a basic setup for a Django application with a sample API endpoint.

### Features

- **Django REST Framework**: Easily create RESTful APIs with Django.
- **ReDoc Documentation**: Generate beautiful, customizable API documentation.
- **Swagger Documentation**: Create interactive, machine and human-readable API documentation..

## Installation and Setup

### Prerequisites

- Python 3.9 or higher
- Django 4.2.15
- pip (Python package installer)
- Git (for version control)

### Installation Steps

1.  **Apply migrations:**

    Prepare the database by applying migrations.

    `python manage.py migrate`

2.  **Run the development server:**

    Start the Django development server.

    `python manage.py runserver`

    By default, the server will start at `http://127.0.0.1:8000/`. You can visit this URL in your web browser to see the project running.

    You can now test the API using these URLs:

-   **GET /api/items/**: List all items.
-   **POST /api/items/**: Create a new item.
-   **GET /api/items/{id}/**: Retrieve a specific item.
-   **PUT /api/items/{id}/**: Update a specific item.
-   **DELETE /api/items/{id}/**: Delete a specific item.

### API Documentation

-   **ReDoc Documentation**: Accessible at `http://127.0.0.1:8000/redoc/`.
-   **Swagger UI**: Accessible at `http://127.0.0.1:8000/swagger/`.

### Usage Instructions

1.  **Run the server** and navigate to the provided URLs to access the API documentation or interact with the API.
2.  **Modify the project** as needed by adding new endpoints, models, or views.
3.  **Explore the API** using the provided documentation tools (ReDoc or Swagger UI).

### Contributing

Contributions are welcome! Please fork the repository, create a new branch for your feature or bugfix, and submit a pull request. Make sure to provide a detailed description of your changes.

