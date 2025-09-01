## End to End Machine Learning Project
This repository contains an end-to-end Machine Learning Project implemented as part of a hands-on learning experience. The project covers everything from problem definition to model deployment, following a structured ML workflow.

**Overview:**
This project demonstrates how to build a machine learning pipeline in a modular and production-ready manner. It focuses on best practices in data ingestion, preprocessing, model training, evaluation, and deployment.

The key objectives of this project are:
1. Understand the machine learning lifecycle.
2. Learn how to structure ML code for scalability and reusability.
3. Implement MLOps fundamentals such as CI/CD, packaging, and deployment.

**Project Workflow**
1. Data Ingestion – Collecting and loading raw datasets
2. Data Transformation – Handling missing values, encoding, feature engineering, and scaling
3. Model Training – Training multiple ML algorithms and selecting the best model
4. Model Evaluation – Checking accuracy, precision, recall, and other performance metrics
5. Model Deployment – Exposing the model via a Flask API for real-world usage
6. CI/CD & Packaging – Using GitHub Actions and setup.py for versioning and automation

**Technology Stack:**
Programming Language: Python
Machine Learning: scikit-learn
Data Processing: pandas, NumPy
Model Deployment: Flask
Version Control: Git & GitHub
Automation & CI/CD: GitHub Actions
Environment Management: virtualenv / conda
Packaging: setup.py, requirements.txt

**What I Learned?**
While working on this project, I gained practical knowledge of:
Structuring an end-to-end ML project in a clean, modular way
Building a custom ML pipeline for preprocessing and training
Using logging & exception handling for debugging and production readiness
Writing a setup.py to make the project installable as a Python package
Implementing CI/CD workflows with GitHub Actions
Deploying ML models using Flask API
Understanding the importance of MLOps practices for real-world applications


**How to Run the Project**

1. Clone the repository
<pre> ```bash git clone https://github.com/your-username/mlproject.git cd mlproject ``` </pre>

2. Create a virtual environment & activate it
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

3. Install dependencies
pip install -r requirements.txt

4. Run the application
python app.py

