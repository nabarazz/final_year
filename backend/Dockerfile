FROM python:3.9

RUN pip install --upgrade pip



ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

WORKDIR /usr/src/backend

COPY ./req.txt /usr/src/req.txt
RUN pip install -r /usr/src/req.txt



COPY . /usr/src/backend

EXPOSE 8000