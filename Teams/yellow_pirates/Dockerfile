FROM python:3.11.4

RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir  numpy pillow

RUN mkdir /app
RUN mkdir /images

COPY ./src/c2.py /app/c2.py
COPY ./src/images/* /images/

ENTRYPOINT ["python", "/app/c2.py"]
