FROM python:3.8.10

WORKDIR /app
COPY requeriments.txt /app/requeriments.txt

RUN pip3 install --no-cache-dir --upgrade -r /app/requeriments.txt

COPY . /app

CMD bash -c "while true; do sleep1; done"

