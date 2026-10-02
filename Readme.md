This project contains the structure and resources used for a data science and machine learning project.

## Project Structure

- `data/` — Contains the different datasets used in the project.
  - `raw/` — Original and immutable data.
  - `external/` — Data obtained from external or third-party sources.
  - `interim/` — Intermediate data that has been transformed but is not yet ready for modelling.
  - `processed/` — Cleaned and prepared data ready for modelling.

- `models/` — Contains trained and serialized machine learning models.

- `notebooks/` — Contains Jupyter notebooks used for data exploration, analysis, communication, and prototyping.

- `src/` — Contains the source code used in the project.
  - `data/` — Scripts for downloading or generating data.
  - `features/` — Scripts for transforming data and creating features for modelling.
  - `model/` — Scripts for training and making predictions with models.