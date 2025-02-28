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

![1](https://github.com/user-attachments/assets/1fa136b7-0895-4aa5-ae6a-41aaa00889a5)

![2](https://github.com/user-attachments/assets/61a0dac4-573e-4589-a743-0f70af230644)

![3](https://github.com/user-attachments/assets/b740939e-cf1e-4b2d-b37b-42f35ebd1f99)

![4](https://github.com/user-attachments/assets/fa25202c-ebc0-471c-990f-63cc6e6af91f)

![5](https://github.com/user-attachments/assets/4e683998-482a-4c9e-9815-8439f01c9fe2)
