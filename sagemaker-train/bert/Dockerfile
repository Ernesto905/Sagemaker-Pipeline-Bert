FROM mosaicml/pytorch:1.13.1_cu117-python3.10-ubuntu20.04

WORKDIR /app

COPY requirements.txt /app/
RUN pip install --no-cache-dir -r requirements.txt

COPY src /app/src/
COPY yamls /app/yamls/
COPY assets /app/assets/
COPY my-copy-c4 /app/my-copy-c4
COPY glue.py /app/
COPY main.py /app/

CMD ["python", "main.py"]
