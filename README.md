<img width="1919" height="1033" alt="Screenshot 2025-08-27 190934" src="https://github.com/user-attachments/assets/60807bae-4d35-42f5-9cd2-15caa2fb62d7" />



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

