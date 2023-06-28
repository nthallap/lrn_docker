FROM python:3.7-alpine3.15
RUN apk add curl
ENV FLASK_APP=app.py
ENV FLASK_RUN_HOST=0.0.0.0

WORKDIR /code
COPY ./ ./
RUN python -m pip install flask
EXPOSE 5000
CMD ["flask", "run"]
