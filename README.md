# Online Testing System

The **Online Testing System (OTS)** is a web application that allows users to sign up, attempt tests, and view their scores and history. This system is designed to make online test-taking simple, user-friendly, and accessible from anywhere.

## Features

- **User Authentication**: Users can sign up and log in to access the platform.
- **Test Selection**: Users can choose tests based on their interests and available subjects.
- **Quiz Attempt**: Users can attempt the selected quizzes.
- **Automated Marking**: The system automatically evaluates the user's responses and provides a score.
- **Result Display**: Users can view their results after completing a test.
- **Test History**: A record of all previously attempted tests and scores is maintained for users to access at any time.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django (Python)
- **Database**: SQLite 
- **Authentication**: Django's built-in authentication system
## Installation and Setup

1. **Clone the repository**:
   
   git clone https://github.com/JyothsnaThangudu/online-testing-system.git
   cd online-testing-system

2. **Create and activate a virtual environment**:
    python3 -m venv venv
    source venv/bin/activate

3. **Install dependencies**:
    pip install -r requirements.txt

4. **Run database migrations**:
    python manage.py migrate
5. **Create a superuser (for admin purposes)**:
    python manage.py createsuperuser

6. **Start the development server**:
    python manage.py runserver

7. **Access the system**:
    ->Go to http://127.0.0.1:8000/ to access the application.
    ->Log in using your credentials or create a new account to get started.

**Future Improvements**
   - Admin Features: Add more functionalities for admin users to create and manage tests.
   - Advanced Reporting: Generate detailed reports on user performance over time.
   - Timed Tests: Implement timers for tests to increase the challenge.

**Contributing**
Feel free to open an issue or submit a pull request if you'd like to contribute. Contributions, feature requests, and bug fixes are welcome!




