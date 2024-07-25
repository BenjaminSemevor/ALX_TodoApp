# Todos App

## Overview
We will build a Todos app that lets users log in, create, view, edit, and complete todos. Users can see the list of todos on the home page and post/edit/delete their own todos if they are logged in. They can also mark their todos as ‘complete’. They will not be able to view other users’ todos. Through this app, we will learn a lot of concepts and solidify our Django API and React knowledge.

We will first create the backend of the app using Django and Django Rest Framework (DRF). After that, we will create the frontend with React and connect the frontend to the backend to complete our Django API – React app. In the last chapter, we will deploy our Django backend on PythonAnywhere, and React frontend on Netlify, to run both backend and frontend in the cloud.

## App Structure
- The Django backend server exposes an API.
- The React frontend calls the API and renders the user interface on the client’s browser.

## Features
- User authentication (signup, login, logout)
- Create, view, edit, and delete todos
- Mark todos as complete
- Secure user-specific data

## Technologies
- Backend: Django, Django Rest Framework (DRF)
- Frontend: React
- Deployment: PythonAnywhere (backend), Netlify (frontend)

## Getting Started
To get started with this project, clone the repository and follow the setup instructions for the backend and frontend.

```bash
# Clone the repository
git clone <repository-url>
cd todos-app

Backend Setup

    Navigate to the backend directory and create a virtual environment.
    Install the dependencies from requirements.txt.
    Run the development server.

bash

cd backend
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

Frontend Setup

    Navigate to the frontend directory and install the dependencies.
    Run the development server.

bash

cd frontend
npm install
npm start

Deployment
Backend

Deploy the Django backend on PythonAnywhere by following their deployment guide.
Frontend

Deploy the React frontend on Netlify by following their deployment guide.
Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

Feel free to modify it according to your project's specific details and repository

```
## Authors
- **Benjamin Semevor**
  - [LinkedIn](https://www.linkedin.com/in/benjamin-semevor-1762395a/)
  - [Twitter](https://x.com/BenSemsGh)
