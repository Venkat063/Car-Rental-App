python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate

python manage.py runserver

python manage.py createsuperuser

Additional Notes
This project uses MySQL as the database backend.

Ensure MySQL server is running before running migrations or starting the app.

Adjust database connection settings appropriately for your environment.

