```bash
pip install dbt-core dbt-bigquery
pip install apache-airflow
pip install apache-airflow-providers-google

airflow db init
airflow webserver --port 8080
airflow scheduler

airflow users  create --role Admin --username admin --email admin --firstname admin --lastname admin --password admin


```