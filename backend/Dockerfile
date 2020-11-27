FROM python:3.8
ENV PYTHONUNBUFFERED 1

ADD /newsapi /newsapi/
ADD requirements.txt /newsapi/
WORKDIR /newsapi

RUN pip install -r requirements.txt