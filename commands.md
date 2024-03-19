#Commmands

django-admin startproject core

python manage.py runserver

#import perintah random secret key
from django.core.management.utils import get_random_secret_key

print(get_random_secret_key())

#SIMPAN PACKAGE
pip freeze > requirements.txt

pip install python-dotenv
Untuk membantu Anda dalam hal tersebut, Anda dapat menambahkan Python-dotenv ke aplikasi Anda untuk membuatnya memuat konfigurasi dari file .env saat ada (misalnya dalam pengembangan) namun tetap dapat dikonfigurasi melalui lingkungan:


pip install --upgrade pip

pip install pytest-django