1. Open visual studio code and open the project folder.

2. Open a new terminal and create a new virtual environment using "python -m venv env"

3. A env folder will be created. Locate "env\Scripts\activate.bat" and run the file.

4. On startup menu, search for "Environment variables". On the dialog box, click on "environment variables". On the system variable section, click on "path". Click new and add the original path of "activate.bat".

5. On VS Code, press CTRL+L.SHIFT+P and search for python interpreter. Select the 'python.exe' file inside the 'env' folder.

6. Download and install 'pgadmin' and 'postresql'.

7. Create a new database in postresql named 'TreatMe' and password '1234'

8. Install these following modules in vs code terminal
pillow
stripe
localflavor
psycopg2
sslcommerz_lib

On the terminal, type "python -m pip install MODULE_NAME"

9. Run these following commands:
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

10. Enter the url "http://127.0.0.1:8000/login/" and enjoy.
