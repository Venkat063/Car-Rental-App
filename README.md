<img width="1919" height="1030" alt="Screenshot 2025-08-27 190712" src="https://github.com/user-attachments/assets/01b00eaf-e341-45c8-8408-4fa637fec3c9" />
<img width="1919" height="1033" alt="Screenshot 2025-08-27 190658" src="https://github.com/user-attachments/assets/64742ca3-05d6-42b3-b3e9-7d1ec043ae8c" />



<img width="1919" height="1033" alt="Screenshot 2025-08-27 190934" src="https://github.com/user-attachments/assets/60807bae-4d35-42f5-9cd2-15caa2fb62d7" />
<img width="1919" height="1032" alt="Screenshot 2025-08-27 190859" src="https://github.com/user-attachments/assets/6eb8ccd3-7bb4-4aa5-9046-778c3354a102" />




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

