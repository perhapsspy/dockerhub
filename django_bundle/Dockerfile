FROM python:3.6
RUN apt-get update && apt-get install -y build-essential nginx supervisor nodejs npm postgresql-client
RUN ln -s /usr/bin/nodejs /usr/bin/node
RUN pip install setuptools pip --upgrade
RUN pip install uwsgi
