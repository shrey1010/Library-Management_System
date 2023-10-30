# Library Management System

## Features

- **Book Management**: Add, edit, and delete books. Each book includes details like title, author, quantity, and subject.

- **User Authentication**: Users can register, login, and logout. Passwords are securely hashed.

- **Book Issuing and Returning**: Registered users can issue and return books. The system keeps track of issue and return dates.

- **History**: Users can view their book borrowing history.

- **Fines**: A fine of Rs. 10 per day is applied for books returned after 15 days.

## Endpoints

- `GET /` : Home page.
- `POST /login/`: Log in.
- `POST /register/`: Register.
- `GET /logout`: Log out.
- `POST /issue`: Issue a book.
- `POST /return_item`: Return a book.
- `GET /history`: View borrowing history.
- `GET /fine/`: View fines for overdue books.

## Setup Instructions

1. Make sure you have Python and Django installed.
2. Clone the repository: `git clone https://github.com/shrey1010/Library-Management_System/`
3. Navigate to the project directory: `cd library_management_system`
4. Create and activate a virtual environment (optional but recommended): 
    ```
    python3 -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```
5. Install dependencies: `pip install -r requirements.txt`
6. Apply migrations: `python manage.py migrate`
7. Start the development server: `python manage.py runserver`
8. Visit `http://localhost:8000` in your browser.

## How to Use

1. Register a new account or log in with existing credentials.
2. From the home page, you can issue or return books, view borrowing history, and check fines for overdue books.

## Dependencies

-Python 3.10
- Django 4.0.1


---

Feel free to reach out if you have any questions or encounter any issues! Happy reading!