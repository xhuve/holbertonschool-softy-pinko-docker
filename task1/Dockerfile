FROM ubuntu:latest

WORKDIR /app

COPY . /app

RUN apt-get update && apt-get upgrade -y

RUN apt-get install -y python3 python3-pip

RUN rm /usr/lib/python*/EXTERNALLY-MANAGED

RUN pip install flask

EXPOSE 5252

ENTRYPOINT [ "python3", "api.py" ]
