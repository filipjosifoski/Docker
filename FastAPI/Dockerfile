FROM python:3

RUN pip install --no-cache-dir fastapi uvicorn

EXPOSE 80

COPY ./app /app

CMD ["uvicorn", "app.main:app", "--host","0.0.0.0", "--port", "80"]

