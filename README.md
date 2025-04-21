# shop3
This id my 3th shop with python. It's an ecommerce website have persian language in front-end.
## Install

To install it:
```
# Unix-like(linux)
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
