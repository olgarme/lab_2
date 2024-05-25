pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
pip install Django psycopg2-binary

python3 manage.py makemigrations crud

python3 manage.py migrate

python3 write.py

python3 read_courses.py

python3 read_instructors.py

python3 read_learners.py
