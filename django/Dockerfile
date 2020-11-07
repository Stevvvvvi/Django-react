FROM python:3

RUN mkdir /app
WORKDIR /app
COPY requirements.txt /app/
RUN pip install -r requirements.txt
# RUN pip install pipenv

# RUN pipenv --three
# # RUN pipenv shell
# RUN pipenv install django djangorestframework django-rest-knox
COPY . /app/
# CMD ["cd","leadmanager","&&","python","manage.py","runserver"]