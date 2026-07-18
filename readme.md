## Student Performance Prediction Project

This repository contains an end-to-end machine learning web application for predicting student performance from demographic and academic input features.

The active project code now lives at the repository root and includes:

- a Flask app for prediction requests
- data ingestion, transformation, and model training pipeline code
- HTML templates for the home page and prediction form
- prepared artifacts and notebook work for experimentation

## Tech Stack

- Python
- Flask
- scikit-learn
- CatBoost
- XGBoost
- pandas and NumPy

## Local Setup

1. Create and activate a virtual environment.

2. Install dependencies:

	```bash
	pip install -r requirements.txt
	```

3. Run the application:

	```bash
	python app.py
	```

4. Open the app in your browser at `http://127.0.0.1:8080`.

## Project Layout

- `app.py` - Flask entry point
- `src/components/` - ingestion, transformation, and training logic
- `src/pipeline/` - prediction pipeline
- `templates/` - HTML pages
- `artifacts/` - generated datasets and model outputs
- `notebook/` - exploratory work and model notebooks

## Notes

- The repository still contains a few copied project folders from the original workspace, but the code being published is the root-level application.
- If you want, I can also clean up the duplicate folders before you continue working.
