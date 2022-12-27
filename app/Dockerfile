FROM python:3.8

WORKDIR /app 
COPY requirements.txt requirements.txt

RUN pip3 install --no-cache-dir --upgrade -r /app/requirements.txt

COPY . / app/

CMD bash -c "whil true; do sleep 1; done"
