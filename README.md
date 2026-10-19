# NYC Taxi Data Cleaning — Lab 3

**Course:** INF4058 — Data Engineering

## Project Overview

This project analyzes and cleans the January 2021 NYC Yellow Taxi dataset using Python and Pandas.

The notebook explores the dataset, checks data types, processes data in chunks, and investigates potential data quality issues such as duplicate records.

## Dataset

The dataset file is named `yellow_tripdata_2021-01.csv.gz`.

Place the dataset in the project directory before running the notebook.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Docker
- Docker Compose

## Run with Docker

1. Install Docker Desktop and start the Docker engine.
2. Open a terminal in the project directory.
3. Build and start the Jupyter environment:

   ```bash
   docker compose up --build -d
   ```

4. Retrieve the Jupyter access URL:

   ```bash
   docker compose logs notebook
   ```

5. Open the local Jupyter URL in your browser and use the token shown in the logs.

## Stop the Environment

```bash
docker compose down
```

## Notes

The Docker configuration provides a containerized Jupyter environment. PostgreSQL integration and the complete data ingestion pipeline must be documented separately if included in the final project.