FROM python:3.9.6-slim-buster

RUN mkdir /app
WORKDIR /app

COPY requirements.txt /app/requirements.txt
RUN chmod 755 requirements.txt
RUN pip3 install -r requirements.txt

COPY . .

CMD ["python3","main.py"]