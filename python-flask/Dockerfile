FROM python:slim-bullseye
WORKDIR /app
COPY app.py .
RUN pip install flask mysql-connector-python
CMD [ "python", "app.py" ]