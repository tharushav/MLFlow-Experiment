# MLFlow-Experiment
This project demonstrates the use of MLflow for tracking machine learning experiments. It uses an ElasticNet model to predict wine quality based on various features.

## Features
- Tracks parameters, metrics, and models using MLflow.
- Logs models and artifacts compatible with DagsHub.
- Includes a simple example using the wine quality dataset.

## Requirements
- Python
- MLflow
- DagsHub

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the script:
   ```bash
   python demo.py <alpha> <l1_ratio>
   ```
   Replace `<alpha>` and `<l1_ratio>` with desired values or leave them blank to use default values.

## Dataset
The wine quality dataset is automatically downloaded from the MLflow repository.

## Notes
- The project is configured to work with DagsHub for MLflow tracking.