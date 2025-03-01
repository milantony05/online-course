# Online Course Application

Online Course is a Django-based web application that allows users to enroll in courses, take assessments, and evaluate their submissions.

**ER Diagram**

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

## Installation

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/milantony05/online-course.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd online-course
   ```
3. **Create and activate a virtual environment**:
   ```bash
   pip install --upgrade distro-info
   pip3 install --upgrade pip==23.2.1
   pip install virtualenv
   python3 -m venv djangoenv
   source djangoenv/bin/activate  # On Windows use `djangoenv\Scripts\activate`
   ```
4. **Install dependencies**:
   ```bash
   pip install -U -r requirements.txt
   ```
5. **Apply migrations**:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
6. **Create a superuser (for admin access)**:
   ```bash
   python manage.py createsuperuser
   ```
7. **Run the server**:
   ```bash
   python manage.py runserver
   ```
8. **Running the application**:<br>
   Admin site: Append `/admin` to the url<br>
   Online course site: Append `/onlinecourse` to the url

## Features

- Course enrollment and management
- Exam and assessment feature
- Question, choice, and submission models
- Score evaluation and result display
- Admin panel for managing courses and assessments

## Technologies Used

- Python
- Django
- PostgreSQL
- Bootstrap (for UI styling)

## Demo

![1](https://github.com/user-attachments/assets/15f4aa42-9d80-48ed-a4e0-5fd771751e22)

![2](https://github.com/user-attachments/assets/2f19a5be-f842-4edc-b617-3d95bd9c1584)

![3](https://github.com/user-attachments/assets/592277ec-4ebc-4ac9-b5c2-3f8239b8e4ba)

![4](https://github.com/user-attachments/assets/0b95d4d3-1354-4870-9c6b-2f512bbe6c22)

![5](https://github.com/user-attachments/assets/ed5c4865-b0bf-4558-8d89-4eaf92d8ee5a)
