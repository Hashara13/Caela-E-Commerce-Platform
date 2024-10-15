# Caela E-Commerce Platform

Caela is an advanced e-commerce platform that combines a Vue.js frontend with a Django backend to deliver an interactive shopping experience and robust data management. This project aims to provide a scalable and feature-rich solution for online retail businesses.

## Features

- User authentication and authorization
- Product catalog with categories and search functionality
- Shopping cart and wishlist management
- Secure checkout process
- Order tracking and history
- User reviews and ratings
- Admin panel for inventory and order management
- Responsive design for mobile and desktop
- RESTful API for seamless frontend-backend communication

## Tech Stack

- Frontend: Vue.js
- Backend: Django
- Database: PostgreSQL
- API: Django Rest Framework

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v14 or higher)
- Python (v3.8 or higher)
- pip (Python package manager)
- PostgreSQL
- Git

## Installation

### Backend (Django)

1. Clone the repository:
   ```
   git clone https://github.com/Hashara13/Caela-E-Commerce-Platform.git
   cd Caela-E-Commerce-Platform/backend
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\\Scripts\\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Set up the PostgreSQL database and update the `DATABASES` configuration in `settings.py`.

5. Apply database migrations:
   ```
   python manage.py migrate
   ```

6. Create a superuser (admin) account:
   ```
   python manage.py createsuperuser
   ```

7. Start the Django development server:
   ```
   python manage.py runserver
   ```

### Frontend (Vue.js)

1. Navigate to the frontend directory:
   ```
   cd ../frontend
   ```

2. Install the required npm packages:
   ```
   npm install
   ```

3. Start the Vue.js development server:
   ```
   npm run serve
   ```

## Usage

1. Access the Django admin panel at `http://localhost:8000/admin/` to manage products, orders, and users.

2. Visit `http://localhost:8080` in your web browser to access the Caela E-Commerce Platform frontend.

3. Register a new account or log in to start shopping and exploring the platform's features.

## API Documentation

API endpoints are documented using Django Rest Framework's built-in documentation. After starting the backend server, you can access the API documentation at `http://localhost:8000/api/docs/`.


## Contact

Hashara - [GitHub Profile](https://github.com/Hashara13)

Project Link: [https://github.com/Hashara13/Caela-E-Commerce-Platform](https://github.com/Hashara13/Caela-E-Commerce-Platform)