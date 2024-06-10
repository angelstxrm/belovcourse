FROM python:3.11

WORKDIR /code

RUN apt update && apt -qy upgrade

COPY requirements.txt /code/
RUN pip install -r requirements.txt

COPY . /code/