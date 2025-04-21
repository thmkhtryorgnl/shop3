# shop3
This my 3th shop with python

## Install

To install it:
```
# Linux or MacOS
git clone https://github.com/thmkhtryorgnl/shop3/archive/refs/heads/main.zip
python -m venv shop3
source shop3/bin/activate
python -m pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
now you can visit it in `http://127.0.0.1:8000` .
for admin go `/admin` and see django admin page .
