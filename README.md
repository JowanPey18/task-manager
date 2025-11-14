# Task Manager App

A task management application built with Django REST Framework and React.js.

# Setup Instructions

##Backend (Django)
1. Open downloaded file. Navigate to the backend folder
Using CMD go to the folder using cd backend

2. Create and activate a virtual environment using:
python -m venv venv
Then activate it using venv\Scripts\activate On CMD
 
3. Install Dependencies
pip install -r requirements.txt

4. Run Migrations on terminal on Visual Studio Code.
python manage.py makemigrations
python manage.py migrate

5. Start the development server on Visual Studio Code:
python manage.py runserver
(API will be available at http://127.0.0.1:8000)

##Frontend (React)
1. Navigate to the frontend folder using cd frontend.

2. Install Dependencies
npm install

3. Start the development server on CMD:
npm start
(App will run at http://localhost:3000)

#If you want to end the application, close browser then click Ctrl+c to stop the process on both terminal and CMD.

---------------------------------------------------------

##API Endpoint Summary

| METHOD | ENDPOINT | DESCRIPTION | 
| GET | /tasks/ | List all tasks | 
| POST | /tasks/ | Create a new task | 
| GET | /tasks/{id}/ | Retrieve a task by ID | 
| PUT | /tasks/{id}/ | Update title & description | 
| PATCH | /tasks/{id}/ | Toggle completed status | 
| DELETE | /tasks/{id}/ | Delete a task | 




