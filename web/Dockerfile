FROM python:3.7
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
COPY requirements.txt /code/
RUN python -m pip install --upgrade pip

RUN python -m pip install -r requirements.txt

COPY . /code/
