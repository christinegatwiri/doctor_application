# Set up

1. Git clone the repository in your desired folder

2. Run `pipenv --python3.10` to setup your virtual environment, or whichever environment you're on

3. After it has been set up successfully, run `pipenv shell` to activate the environment.

4. Run `pipenv install` to install the packages used. 

5. Creat your `.env` file and add the required fields

6. Setup the postgres database locally, using the settings in the `.env` file.

7. Run `python manage.py migrate` to apply migrations to your db

8. Run `python manage.py createsuperuser` and create a superuser

9. Run `python manage.py runserver` to run your server on `http://localhost:8000`