# Kidney Disease Classification using MLflow and DVC

## Overview
This project aims to build a robust kidney disease classification system using machine learning (ML) and deep learning techniques. By leveraging MLflow for experiment tracking, DVC (Data Version Control) for data management, and Docker for containerization, the project ensures reproducibility, scalability, and ease of deployment. A user-friendly Flask-based frontend allows users to upload images for real-time classification.

## Key Features
- **Accurate Classification**: Utilizes advanced deep learning models (such as Transformers from HuggingFace) to achieve high accuracy in kidney disease classification.
- **Experiment Tracking**: Logs and manages experiments using MLflow, facilitating comparison of model runs, hyperparameters, and metrics.
- **Data Management**: Ensures version control and management of datasets with DVC, enabling seamless collaboration and reproducibility.
- **Containerization**: Dockerizes the application for easy deployment and scalability across different environments.
- **CI/CD Pipeline**: Implements a CI/CD (Continuous Integration/Continuous Deployment) process to automate testing, building, and deployment of the application.

## Project Benefits
- **Improved Diagnostic Accuracy**: Enhances the precision of kidney disease diagnosis, supporting healthcare professionals in making informed decisions.
- **Reproducibility**: Ensures that experiments and results can be reproduced reliably, crucial for research and clinical settings.
- **Scalability**: Facilitates easy scaling of the system with increased data volume and user demand.
- **User-Friendly Interface**: Provides an intuitive web interface for seamless interaction, enhancing usability and accessibility.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Flask, Python
- **CI/CD**: MLflow, DagHub, DVC (Data Version Control)
- **Deep Learning**: Transformers, HuggingFace, TensorFlow, PyTorch
- **Tools**: Docker, VSCode, GitHub

## Working and Pipeline Stages

### Working
1. **Data Ingestion**: Raw data is collected and preprocessed to ensure it meets the requirements for model training.
2. **Base Model Preparation**: A baseline model is developed using deep learning frameworks like TensorFlow or PyTorch to establish initial performance benchmarks.
3. **Model Training**: Deep learning models are trained using labeled data, optimizing hyperparameters to improve accuracy and generalization.
4. **Model Evaluation**: Trained models are evaluated using metrics such as accuracy, precision, recall, and F1 score to assess performance.
5. **Integration with MLflow and DVC**: Models, experiments, and datasets are logged and version-controlled using MLflow and DVC respectively, ensuring reproducibility and collaboration.

### CI/CD Process
The CI/CD pipeline automates the following stages:
- **Continuous Integration**: Automatically tests code changes pushed to GitHub to maintain code quality and identify issues early.
- **Build**: Automatically builds Docker images with updated code and dependencies.
- **Automated Testing**: Runs automated tests to verify the functionality and performance of the application.
- **Deployment**: Automatically deploys the Dockerized application to production or staging environments, ensuring that the latest version is always available for use.

## Conclusion
This project showcases the effective integration of advanced machine learning techniques with robust software engineering practices. By leveraging MLflow, DVC, Docker, and implementing a CI/CD pipeline, the project not only achieves high accuracy in kidney disease classification but also ensures scalability, reproducibility, and ease of deployment, making it a valuable asset in healthcare diagnostics.

For more details about the project, feel free to explore the full project code and report on GitHub:
[GitHub Repository](https://github.com/Pathakdarshan12/Kidney_Disease_Classification_MLflow_DVC.git)


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)
