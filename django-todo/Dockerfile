FROM python:3.8-slim-buster

Env djangotodo

WORKDIR django-todo

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

EXPOSE 8000

CMD ["python3","manage.py","runserver"]

