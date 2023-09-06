FROM python:slim

WORKDIR /app

COPY . /app/

RUN ls

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

CMD ["python", "worker.py"]