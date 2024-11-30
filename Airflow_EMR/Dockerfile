FROM apache/airflow:latest
COPY config_file.toml .
RUN pip install toml \
    && pip install apache-airflow-providers-amazon