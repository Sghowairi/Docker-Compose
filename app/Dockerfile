FROM python:3.7

WORKDIR /app

COPY requirements.txt  .

RUN pip install -r requirements.txt && pip install psycopg2-binary

COPY . .

CMD ["python", "app.py"] 
