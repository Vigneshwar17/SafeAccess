# SafeAccess - Secure Authentication Platform

A secure authentication platform built with Flask, featuring user registration, login, and session management with password hashing.

## Features

- **User Registration**: Secure signup with email validation and password strength requirements
- **User Authentication**: Login system with hashed password verification
- **Session Management**: Protected routes using Flask sessions
- **Responsive Design**: Bootstrap-powered UI that works on all devices
- **Security Features**: Password hashing, input validation, and session protection
- **Clean UI**: Modern, professional interface with smooth animations

## Tech Stack

- **Backend**: Python + Flask
- **Frontend**: HTML, CSS, Bootstrap 5
- **Database**: SQLite with Flask-SQLAlchemy
- **Authentication**: Flask sessions + Werkzeug password hashing
- **Icons**: Font Awesome

## Installation

1. Clone or download the project files
2. Install dependencies:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`
3. Run the application:
   \`\`\`bash
   python app.py
   \`\`\`
4. Open your browser and go to `http://localhost:5000`



## Security Features

- **Password Hashing**: Uses Werkzeug's secure password hashing
- **Input Validation**: Server-side and client-side form validation
- **Session Protection**: Dashboard accessible only to authenticated users
- **Email Validation**: Proper email format checking
- **Password Strength**: Minimum 6 characters requirement
- **SQL Injection Protection**: SQLAlchemy ORM prevents SQL injection

## Usage

1. **Sign Up**: Create a new account with name, email, and password
2. **Sign In**: Login with your email and password
3. **Dashboard**: Access your protected dashboard after authentication
4. **Logout**: Securely end your session



## Customization

- Update the secret key in `app.py` for production use
- Modify the database URI for different database systems
- Customize the UI by editing the CSS in `static/style.css`
- Add more fields to the User model as needed

## Production Notes

- Change the `SECRET_KEY` to a secure random value
- Use a production database (PostgreSQL, MySQL)
- Enable HTTPS
- Add rate limiting for login attempts
- Implement password reset functionality
- Add email verification for new accounts
