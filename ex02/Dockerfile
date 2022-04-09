FROM python:3.9-slim

WORKDIR /tmp/mydir

COPY requirements.txt ${PWD}

RUN pip install -r requirements.txt

ARG wdir

WORKDIR $wdir