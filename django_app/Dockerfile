FROM python:3.7-alpine3.15


WORKDIR /code
COPY ./naga/ ./
RUN python -m pip install Django 
 
EXPOSE 8000
CMD ["python3", "manage.py", "runserver", "0:8000", "--noreload"]
#CMD ["echo", "hello"]
