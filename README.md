# Login Authentication App (Flask + MongoDB)

A simple and secure login authentication web application built with **Flask** and **MongoDB Atlas**. The app supports **user registration**, **login/logout**, and a **protected (secured) page** that is accessible only after successful authentication. Passwords are securely stored using **bcrypt hashing**, and sessions are handled using Flask’s built-in session management.

---

## Features

- User registration with: **first name, last name, username, password**
- Secure password hashing with **Flask-Bcrypt**
- User login with credential validation and session creation
- Protected route (`/secured`) accessible only for logged-in users
- Logout functionality that clears the session
- MongoDB collections used:
  - `register` for user accounts
  - `login_sessions` for login tracking
- Frontend UI built with HTML/CSS and Font Awesome, including password show/hide toggle in JavaScript

---

## Tech Stack

- **Backend:** Flask (Python) :contentReference
- **Database:** MongoDB Atlas (Flask-PyMongo / PyMongo) :contentReference
- **Security:** Flask-Bcrypt (password hashing) :contentReference
- **Frontend:** HTML, CSS, JavaScript :contentReference
- **Config:** python-dotenv (.env environment variables) :contentReference

---

## Project Structure

- static/ # CSS + JavaScript
- templates/ # HTML pages
- app.py # Flask application entry point
- .env # environment variables (not committed)
- requirements.txt
