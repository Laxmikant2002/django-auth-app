# Django Auth Project

## Setup Instructions

To run this Django project and set up a `.env` file for environment variables, follow these steps:

### 1. Install Dependencies
Make sure you have Python and pip installed. Then, install the required dependencies:
```sh
pip install django python-dotenv
```

### 2. Create a .env File
Create a .env file in the root directory of your project (where manage.py is located). Add the following environment variables:
```sh
EMAIL_USER=your-email-user
EMAIL_PASS=your-email-password
```

3. Run the Project
Run the following commands to apply migrations and start the development server:
```sh
python manage.py migrate
python manage.py runserver
```

4. Access the Application
Open your web browser and navigate to http://127.0.0.1:8000/ to access the application.
