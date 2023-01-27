FROM python:alpine

WORKDIR /app

RUN pip install pymongo

COPY . .

CMD [ "python3", "main.py" ]