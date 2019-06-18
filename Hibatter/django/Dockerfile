FROM python:3
ENV LANG en_US.utf8
WORKDIR /code
ADD requirements.txt /code
RUN apt-get update
RUN pip3 install -r requirements.txt 
RUN apt-get install -y mysql-client
