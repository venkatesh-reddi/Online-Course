# Online Course App with Django

## Introduction

I developed an Online Course App using Django. The app facilitates course management, enrollment, and assessments for learners. It features models for instructors, learners, courses, lessons, enrollments, questions, choices, and submissions, providing a comprehensive solution for online education.

## Features

- User registration and authentication
- Course creation and management
- Enrollment system for courses
- Lesson content organization
- Assessment through questions and choices
- Submission tracking and result calculation

## Technologies Used

- **Django**: The main web framework used for developing the app
- **Python**: The programming language used
- **SQLite**: Database used for development
- **HTML/CSS**: For frontend templates

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/venkatesh-reddi/Online-Course.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Online-Course
    ```

3. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

5. Apply the migrations:

    ```bash
    python manage.py migrate
    ```

6. Create a superuser:

    ```bash
    python manage.py createsuperuser
    ```

7. Run the development server:

    ```bash
    python manage.py runserver
    ```

## Usage

1. Access the app at `http://127.0.0.1:8000`.
2. Register as a new user or log in with the superuser credentials.
3. Create and manage courses, enroll learners, and organize lessons.
4. Learners can enroll in courses, submit assessments, and view their results.

## Entity Relationship Diagram

You can view the entity relationship diagram below.

![Onlinecourse ER Diagram](https://github.com/venkatesh-reddi/Online-Course/blob/main/static/media/course_images/onlinecourse_app_er.png)

## Contribution

Feel free to contribute to this project by opening issues and submitting pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the Apache 2.0 License.

---

Happy coding! If you have any questions or need further assistance, please don't hesitate to reach out.

---

Venkatesh Reddi

[GitHub Profile](https://github.com/venkatesh-reddi) | [LinkedIn Profile](https://linkedin.com/in/venkateshreddi)
