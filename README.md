# Export Control Classification Hierarchy App

This project focuses on creating an interactive application that allows users to generate a hierarchical classification of Export Control classes (Regulation Categories) based on text input. The app leverages the Code of Federal Regulations (CFR) to provide accurate and legally compliant classifications. The generated hierarchy can be used to call APIs or web services to further manage and process export control data.

## Project Objectives

- **Text Input Parsing:** The app should accept text input related to export control regulations.
- **Regulation Classification:** Based on the text input, the app will refer to the Code of Federal Regulations (CFR) to determine the relevant export control classes.
- **Hierarchy Generation:** A hierarchical representation of export control classes will be generated dynamically.
- **UI/UX Design:** An intuitive user interface (UI) will allow users to interact with the app and visualize the classification hierarchy.
- **API/Web Services Integration:** The app will provide an option to call external APIs or web services based on the generated hierarchy.

## Features

- **Text Input Analysis:** Users can input text, and the app will analyze and identify relevant export control classes.
- **Dynamic Hierarchy Visualization:** Generates a tree-like structure of classes that are relevant to the input text.
- **API Integration:** The app can be configured to call specific APIs/web services with the generated hierarchy data.
- **Export and Save Options:** Users can export the generated hierarchy in various formats (e.g., JSON, XML) and save it locally or to a cloud service.

## Project Structure

- `data/`: Folder for datasets and reference texts related to CFR.
- `src/`: Source code for text parsing, regulation classification, and hierarchy generation.
- `ui/`: Code for UI components and front-end integration.
- `api/`: API service definitions and integration scripts.
- `notebooks/`: Jupyter notebooks for experimentation and prototyping.
- `models/`: Trained models (if any) and classification algorithms.
- `reports/`: Generated analysis, summary reports, and user guides.

## Workflow for Export Control Class Hierarchy

The workflow is compatible with AWS, Azure, and Google Cloud, and follows these steps:

## Workflow Overview

### 1. Data Ingestion
- **Description:** Collect data from CFR and relevant sources.
- **Cloud Storage:** Use services like Azure Blob Storage for fast access.

### 2. Data Preprocessing
- **Description:** Clean data using NLP techniques such as tokenization, lemmatization, and removing stop words.
- **Cloud Services:** Perform preprocessing using tools like Azure Functions or AWS Lambda.
- **Output:** Store cleaned data in cloud storage.

### 3. Feature Engineering
- **Description:** Extract text features using methods like TF-IDF, Word2Vec, and GloVe.
- **Output:** Save processed data and features in cloud storage.

### 4. Model Training
- **Description:** Train an NLP model to classify text into Export Control classes.
- **Cloud Tools:** Use hyperparameter tuning services like Azure ML HyperDrive or AWS SageMaker.
- **Output:** Store the trained model for further evaluation.

### 5. Model Evaluation
- **Description:** Evaluate the model's performance using F1-score, precision, and recall.
- **Validation:** Ensure the model is not overfitting by validating on a separate dataset.

### 6. API Integration
- **Description:** Call APIs to create a class hierarchy based on the classification output.
- **Cloud Services:** Use API management services like Azure API Management or AWS API Gateway.

### 7. Deployment
- **Description:** Deploy the model as a REST API.
- **Cloud Tools:** Utilize Azure Web Services or AWS SageMaker endpoints.
- **UI Deployment:** Deploy the widget or app using Azure App Service or AWS Amplify.

### 8. Continuous Monitoring
- **Description:** Monitor model performance and API usage.
- **Cloud Monitoring:** Use Azure Monitor or AWS CloudWatch for logging and scaling services like Azure Autoscale or AWS Auto Scaling.

### 9. CI/CD Pipeline
- **Description:** Set up a CI/CD pipeline to automate workflows including data ingestion, model training, and deployment.
- **Cloud Tools:** Use Azure DevOps or AWS CodePipeline for automated deployment with validation tests.

## Workflow Diagram
![MLOps Workflow](path_to_the_diagram_in_your_repo.png)
