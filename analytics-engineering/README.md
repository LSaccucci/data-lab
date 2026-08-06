# analytics-engineering

This folder is the analytics-engineering subrepository for the data-lab project.

Purpose
- Host analytics engineering artifacts: data models, transformation pipelines, documentation, and CI for analytics workflows.

Suggested structure
- docs/                -> Design docs, onboarding, conventions
- src/                 -> Transformation code (dbt, SQL, Python scripts)
- pipelines/           -> Orchestration definitions (Airflow, Dagster, etc.)
- tests/               -> Unit/integration tests for transformations
- data_samples/        -> Small sample datasets for local testing

Getting started
1. Pick a transformation framework (dbt recommended for SQL-first modeling).
2. Add framework-specific config (e.g., dbt_project.yml) under this directory.
3. Add CI pipeline or job definitions in pipelines/.

Next steps
- If you want, I can scaffold a specific framework (dbt, Airflow, Dagster) with example files and CI. Tell me which one and any preferences (branch name, license, template).
