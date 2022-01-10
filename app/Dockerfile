FROM python:3.7

COPY requirements.txt /app/

WORKDIR /app

RUN pip install -r requirements.prod.txt

COPY . /app

EXPOSE 5000

CMD ["uwsgi", "--ini", "wsgi.ini"]