FROM python:3.7.8

RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y --no-install-recommends cmake # for xlearn install
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
WORKDIR /app
COPY requirements.txt ./
