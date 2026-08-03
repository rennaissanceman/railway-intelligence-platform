# Railway Intelligence Platform

An end-to-end machine learning project for analyzing railway operations
and predicting train delays.

## Project status

Work in progress — initial project setup.

## Project goals

- collect and validate historical railway data;
- analyze delays and railway operations;
- build reproducible data-processing pipelines;
- engineer time-aware, route-related and operational features;
- train machine learning models for delay prediction;
- evaluate models using time-aware validation;
- expose predictions through an API and web application;
- deploy the application online.

## Planned workflow

1. Data acquisition
2. Data validation and preprocessing
3. Exploratory data analysis
4. Feature engineering
5. Baseline model development
6. Time-aware model validation
7. Experiment tracking and model selection
8. Prediction API
9. Web application
10. Online deployment and monitoring

## Project structure

```text
railway-intelligence-platform/
├── configs/                  # Project and experiment configuration
├── data/
│   ├── external/             # Data obtained from external sources
│   ├── interim/              # Intermediate transformed data
│   ├── processed/            # Data prepared for modeling
│   └── raw/                  # Original, immutable source data
├── models/                   # Trained model artifacts
├── notebooks/                # Exploratory notebooks
├── reports/
│   └── figures/              # Generated charts and visualizations
├── src/
│   └── railway_intelligence_platform/
│                              # Application and ML source code
├── tests/                    # Automated tests
├── pyproject.toml
└── README.md

## Technology stack

- Python 3.11
- uv
- pandas
- NumPy
- scikit-learn
- PyArrow
- Pydantic Settings
- pytest
- Ruff

## Development setup

Install the project and its dependencies:

```powershell
uv sync
```

Run the test suite:

```powershell
uv run pytest
```

Check the source code with Ruff:

```powershell
uv run ruff check .
```

Check code formatting:

```powershell
uv run ruff format --check .
```

## Data and model artifacts

Raw data, processed datasets and trained models are not stored directly
in the Git repository. Their directories are preserved using `.gitkeep`
files and their contents are excluded through `.gitignore`.

## License

License to be selected.