FROM python:3.8

WORKDIR /pyapp

COPY requirements.txt .

RUN pip install -r requirements.txt


COPY . .

EXPOSE 8080

CMD ["python3", "./pyapp/main.py"]