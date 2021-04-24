# reddit

A website for posting posts and giving votes for each post ( almost like reddit and stackoverflow websites )

# description

1- user authentication by using django.contrib.auth.models
2- users can post and delete their posts
3- each user can vote for each post and can remove his vote

# installation

## using virtual environment

1- run -> `python -m venv <any name>` <br/>
2- to activate your visual environment:
run -> `source <the name you had named>/bin/activate` or `source <the name you had named>/scripts/activate`<br/>
3- to install the requirements run `pip install -r requirements.txt` or `pip3 install -r requirements.txt`<br/>
4- run -> `python manage.py makemigrations`<br/>
5- run -> `python manage.py migrate`<br/>
6- run -> `python manage.py runserver`

## without using virual environment

1- install the requirements: run -> `pip install -r requirements.txt `<br/>
2- run -> `python manage.py makemigrations` <br/>
3- run -> `python manage.py migrate`<br/>
4- run -> `python manage.py runserver`<br/>
