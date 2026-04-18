# Burnout MLOps Prediction System

## Process I followed to start with this project.

- Create an empty git repository.
- In my local system, uv, uvx, kedro is pre-installed as a prerequisites.
- Used `uvx kedro new --name=burnout` with lint, logging and data as additional tools added through CLI prompts.
- `uv sync` and `source .venv/bin/activate`.
- Created 3 pipelines i.e. `feature_engineering`, `training` and `evaluation` through below commands:
    - `kedro pipeline create feature_engineering`
    - `kedro pipeline create training`
    - `kedro pipeline create evaluation`



