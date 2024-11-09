# Data Pipeline with Airflow and Astro
This project is a Weather ETL Pipeline that fetches daily weather data for a specified location, </br>
processes it using Airflow, and loads it into a PostgreSQL database running in a Docker container. </br>
This setup is useful for storing and querying historical weather data for analysis.</br>

## Structure
`dags/`: Contains the Airflow DAG (`etlweather.py`), which orchestrates the pipeline.
`docker-compose.yml`: Configures the PostgreSQL database container.
`Dockerfile`: Defines the environment to run Airflow and the pipeline.

## Setup
1. Clone the repository.
2. Set Up PostgreSQL with Docker Compose.
3. Configure Airflow Connections using POSTGRES_CONN_ID and API_CONN_ID for PostgreSQL and HTTP connection.
4. Run the pipeline using Astro.

## Airflow 
![Screenshot 2024-11-09 at 11 50 45 PM](https://github.com/user-attachments/assets/0800bfa6-9797-48f7-8925-a2743efefb39)
