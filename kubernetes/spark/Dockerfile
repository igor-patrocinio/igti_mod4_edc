FROM gcr.io/spark-operator/spark-py:v3.0.0
LABEL MAINTEINER Carlos Barbosa
LABEL EMAIL carlos.barbosa@a3data.com.barbosa

USER root:root

RUN mkdir -p /app

COPY ./jars /opt/spark/jars

WORKDIR /app

USER root
