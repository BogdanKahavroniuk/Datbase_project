FROM python:3.7.9-slim-buster

WORKDIR /app

RUN pip install --upgrade pip
COPY requirements.txt ./requirements.txt
RUN pip install -r requirements.txt

COPY .. .


CMD ["python", "main.py"]

