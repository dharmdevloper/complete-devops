FROM python3.10

WORKDIR /djangoapp

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

EXPOSE 8001

CMD ["python3","manage.py","runserver"]

