FROM python:3.8

ENV PYTHONUNBUFFERED 1

WORKDIR /api_testing

COPY requirements.txt /api_testing/requirements.txt

RUN pip3 install -r requirements.txt

COPY . /api_testing
