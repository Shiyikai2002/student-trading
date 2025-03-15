Copy student_trading.zip to the target device and place it in an appropriate directory, for example:cd ~/Documents/
Then extract the file:unzip student_trading.zip
Next, enter the project directory:cd student_trading

On the target device, create a Python virtual environment:python -m venv venv
Then activate the virtual environment:
venv\Scripts\activate  # Windows  
source venv/bin/activate  # macOS/Linux

Run the following command in the activated virtual environment:pip install -r requirements.txt
This command will install all dependencies listed in requirements.txt.

If the project uses SQLite, ensure that the db.sqlite3 file has been copied over.
python manage.py makemigrations
python manage.py migrate

Finally, start the Django server:
python manage.py runserver
Then access the web application in your browser:
http://127.0.0.1:8000/

To log in as a regular user:
Username: fhf
Password: 123456gla

To access the Admin Dashboard:
URL: http://127.0.0.1:8000/admin_dashboard/
Username: syk666
Password: 975997174syk

Deployed Project URL
 Project is hosted at: https://student-trading-dbtm.onrender.com
