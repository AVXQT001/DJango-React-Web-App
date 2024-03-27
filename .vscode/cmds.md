# Django & React Web App

[Project-Video](https://youtu.be/c-QsfbznSXI)

- By Tech With Tim @ 27-03-2024 | 04:30:12 PM
- Authentication, Databases, Deployment & More

---

# CMDS
##  Backend
1. Setting up python Environment:
    - `python -m venv env`

2.  Activating the environment: 
    - `env\Scripts\activate` (Windows)

3.  Installing packages using pip by requirements.txt:
    - `pip install -r requirements.txt`

3. Setting Django Project:
    - `django-admin startproject backend`

4. Go to backend folder:
    - `cd backend`

5. Setup django app within project:
    - `python manage.py startapp api`

6. Make migrations for new app and database setup:
    - `python manage.py makemigrations`

7. To migrate the app:
    - `python manage.py migrate`

8. Run the App:
    - `python manage.py runserver`


## Frontend
1. Using vite to create React app:
    - `npm create vite@latest frontend -- --template react`

2. To install Some Packages:
    - `npm install axios react-router-dom jwt-decode`

3. Run the React-App
    - `npm run dev`