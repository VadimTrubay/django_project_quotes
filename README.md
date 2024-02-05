# Django Project Quotes

## Getting Started

- Clone the project repository from
  GitHub: https://github.com/VadimTrubay/django_project_quotes.git

- Install PostgreSQL and create a database for the project.

- Set up a virtual environment and install the project dependencies using the following commands:

~~~
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
~~~

- Configure the database settings and other critical information as environment variables. Do not commit sensitive data
  to
  the repository.

- Run database migrations to create necessary tables:

~~~
python manage.py migrate
~~~

- Create a superuser for the application to access the admin interface:

~~~
python manage.py createsuperuser
~~~

- Start the Django development server:

~~~
python manage.py runserver
~~~

- Access the application via the web browser at http://127.0.0.1:8000/ and log in using the superuser credentials.

# Used technologies:

- Python
- Django
- PostgreSQL
- Bootstrap
- HTML5
- CSS3
- GitHub

- Author - https://github.com/VadimTrubay/django_project_quotes

