FROM python:3.14.0rc1-slim-bullseye

WORKDIR /app/
COPY requirements.txt /app/
RUN pip install -r requirements.txt

COPY . .

EXPOSE 8000 8443

ENTRYPOINT [ "/app/entrypoint.sh" ] 