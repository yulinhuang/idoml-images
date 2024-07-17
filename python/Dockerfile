ARG PYTHON_VERSION="3.12"
FROM python:${PYTHON_VERSION}-slim

RUN apt-get update && apt-get install -y \
    curl


COPY requirements.txt .

RUN pip install -r requirements.txt