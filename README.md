open your command line and run ;
git clone https://github.com/NobleSalt/Web.git
pip install -r requirements.txt
python manage.py migrate
python manage.py makemigrations
python manage.py runserver