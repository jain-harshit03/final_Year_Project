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
