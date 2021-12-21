FROM python:3.7
COPY requirements.txt /app/
WORKDIR /app
RUN pip install -r requirements.txt
COPY . /app

CMD ["uwsgi", "--socket", "0.0.0.0:5000", "--protocol=http", "-w", "wsgi:app"]