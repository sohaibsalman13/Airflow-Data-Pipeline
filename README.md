# Data Pipeline with Airflow and Astro
This project is a Weather ETL Pipeline that fetches daily weather data for a specified location, </br>
processes it using Airflow, and loads it into a PostgreSQL database running in a Docker container. </br>
This setup is useful for storing and querying historical weather data for analysis.</br>

## Structure
`dags/`: Contains the Airflow DAG (`etlweather.py`), which orchestrates the pipeline.</br>
`docker-compose.yml`: Configures the PostgreSQL database container.</br>
`Dockerfile`: Defines the environment to run Airflow and the pipeline.</br>

## Setup
1. Clone the repository.
2. Set Up PostgreSQL with Docker Compose.
3. Configure Airflow Connections using POSTGRES_CONN_ID and API_CONN_ID for PostgreSQL and HTTP connection.
4. Run the pipeline using Astro.

## Airflow 
![Screenshot 2024-11-09 at 11 50 45 PM](https://github.com/user-attachments/assets/0800bfa6-9797-48f7-8925-a2743efefb39)

## Data Access
The loaded data can then be accessed and queryed using any database administration such as Dbeaver. </br>
Make connection to PostgreSQL using authentication credentials
