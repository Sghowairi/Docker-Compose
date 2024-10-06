FROM python

WORKDIR /app

COPY .  .

RUN pip install -r requirements.txt && pip install psycopg2-binary

CMD ["python", "app.py"] 
