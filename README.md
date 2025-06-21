# AAI 540 - Group 5 - DDoS Detection

This project implements a gradient boosting model to classify whether network traffic is benign or part of a distributed denial-of-service (DDoS) attack. 
The model aims to provide real-time detection and reduce the burden on security teams by flagging potential threats for further investigation.

## Key Files
* **athena-setup.ipynb**: loads the data from the [CIC-IDS2017](https://www.unb.ca/cic/datasets/ids-2017.html) dataset into AWS Athena for processing.
* **eda.ipynb**: performs initial exploratory data analysis on the dataset.
* **feature-engineering.ipynb**: preprocesses and encodes the feature data for use in model training.
* **data-splitting.ipynb**: divides the data into separate datasets for training, validation, and final testing.
* **heuristic.ipynb**: implements a basic heuristic model as a baseline for comparison.
* **model-training.ipynb**: trains a gradient boosting model for DDoS traffic identification.
* **model_evaluation_and_deployment**: evaluates the performance of the heuristic and gradient boosting models.
* **monitoring.ipynb**: implements data and infrastructure monitoring, showing key metrics on a Cloudwatch dashboard.
* **ci-cd-pipeline.ipynb**: implements a CI/CD pipeline for automated model deployment.