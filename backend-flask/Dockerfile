FROM python:3.10-slim-buster

# Inside Container
# make a new folder inside the container
WORKDIR /backend-flask

# This contains the libraries we want to install
COPY requirements.txt requirements.txt

# Install the python libraries used for the app
RUN pip3 install -r requirements.txt

COPY . .

ENV FLASK_ENV=development

EXPOSE ${PORT}

RUN apt-get update && apt-get install -y curl

COPY ./external.sh /

RUN chmod +x /external.sh

ENTRYPOINT ["/external.sh"]