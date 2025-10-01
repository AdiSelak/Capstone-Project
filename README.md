# Capstone Project: Machine Learning and Explainable AI for Cybersecurity
- This repository includes the technical tools and implementations that I completed for a group Capstone project. The project was to create a machine learning model for threat detection on the USNW-NB15 dataset and use explainable AI to evaluate the decision making process of black-box models.

Datasets
- USNW-NB15 Dataset.

Models
- models - Contains the dynamic Neural Network model. The models used in this repository are saved versions that have been previously trained.

Tests
- Tests conducted in the project are not included in this repository.

Reports
- Evaluations using SHAP on the Neural Network model and multi-class XG-Boost classifier. The reports provide an example of how to evaluate some of the network traffic data through the SHAP class for both implementations. Additionally some extra context is provided about how using SMOTE sampling and multi-class labels affect the Shapley values.

Tools
- encoder: For encoding features using correlation to the binary label.
- data_visualiser: A tool for visualising within label data to guide the scaler used for a Neural Network.
- shapmanager: Used to streamline SHAP visualisations with additional functions such as categorical labeling, grouping of features, color optimisation, etc.

User Guides
- Example code of using the SMOTE Neural Network and multi-class X-Boost implementations with the encoder, visualiser, and shap manager class.

Project Collaborators:
- Mathew Coleman (Project Management, General Documentation, Validation Testing)
- Scott Chandler (Document Management, General Documentation, Validation Testing, Research)
- Edric Laitly (Scrum Management, General Documentation, User Acceptance Testing)
- Ramandeep Singh (UX Development and Design, General Documentation, UX User Guide, Research)
- Adi Selak (Machine Learning and Tools Design, General Documentation, Pipeline Testing, Code User Guide)

Project Sponsors:
- Dr. Siamak Mirzaei
- Benham Khayer

Project Stakeholder
- Dr. Abdullahi Chowdhury
