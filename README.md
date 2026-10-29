# Artur Liashenko

**Junior Data Engineer** in Valencia, Spain · open to roles in Spain and remote or hybrid across the EU.

I'm moving into data engineering from professional kitchens. For about a year I have been learning
hands-on through mentorship from a senior developer, self-study and the projects below. I care
about pipelines that are tested, reproducible and honest about what they do.

## Projects

| Project | What it shows | Stack |
| --- | --- | --- |
| [Chicago Crime Spark Pipeline](https://github.com/ArturLy263/chicago-crime-spark-pipeline) | Cleaning, enriching and modelling the full Chicago crime dataset (8.5M rows) in a notebook on a mentor-provided AWS EMR cluster, outputs to S3 as Parquet and JSON; the same logic packaged as a PySpark job with an explicit schema, year-partitioned output and tests on synthetic data in CI (not yet re-run on EMR) | PySpark, AWS EMR, S3, Parquet, pytest, GitHub Actions |
| [RestaurantOS](https://github.com/ArturLy263/restaurant-os) | Restaurant order, kitchen and billing backend based on my kitchen experience: PostgreSQL schema with Alembic migrations, row locking, idempotency keys, role-based access, transactional outbox with a delivery worker, WebSocket streams to a React kitchen display; CI with unit, integration and migration tests | Python, FastAPI, PostgreSQL, SQLAlchemy, Alembic, pytest, React, TypeScript, GitHub Actions |
| [NYC Taxi Spark ETL](https://github.com/ArturLy263/nyc-taxi-spark-etl) | Modular PySpark ETL: validation filters, feature engineering, window-function analytics, date-partitioned Parquet output, end-to-end tests on synthetic data; a demo Airflow DAG runs it with input and output checks | PySpark, Parquet, pytest, Airflow (demo), GitHub Actions |
| [Retail sales pipeline](https://github.com/ArturLy263/data_processing_project) | pandas pipeline on synthetic data: input validation, as-of join of sales to stock snapshots, 30-day rolling revenue, top SKUs per region; optional atomic load into PostgreSQL; reproducible, tested in CI | Python, pandas, NumPy, PostgreSQL, pytest, GitHub Actions |

## Skills

- **Used in these projects:** Python, SQL, PostgreSQL, PySpark, pandas, NumPy, SQLAlchemy,
  Alembic, FastAPI, pytest, Git, Docker Compose, GitHub Actions, AWS S3 and EMR
- **Currently learning:** Apache Airflow (first DAG: [NYC Taxi ETL](https://github.com/ArturLy263/nyc-taxi-spark-etl/tree/main/orchestration)), Databricks

## Languages

Ukrainian and Russian (native) · English (B2) · Spanish (B2)

## Contact

[LinkedIn](https://www.linkedin.com/in/artur-liashenko/)
