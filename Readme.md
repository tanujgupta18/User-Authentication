# User Authentication

This project is a Django application focused on user authentication, providing secure registration, login, logout, and password reset functionality.

## Features

- User registration: Allows users to create new accounts with a unique username and email address.
- User login: Secure login system with validation for username/email and password.
- User logout: Allows users to securely log out of their accounts.
- Password reset: Password reset functionality via email, allowing users to regain access to their accounts if they forget their passwords.
- Customizable user model: Custom user model included for flexibility in extending user functionality.
- CSRF protection: Protects against Cross-Site Request Forgery attacks.

## Installation

1. Clone the repository:

```
git clone https://github.com/tanujgupta18/user-authentication.git
```

2. Run the development server:

```
python manage.py runserver
```

The application will be accessible at `http://localhost:8000`.

## Usage

- Visit `http://localhost:8000/register` to create a new user account.
- Visit `http://localhost:8000/login` to log in to an existing account.
- Visit `http://localhost:8000/logout` to log out of the current session.
- Visit `http://localhost:8000/password_reset` to reset your password if you've forgotten it.
- Customize templates, views, and forms as needed for your specific authentication requirements.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.
