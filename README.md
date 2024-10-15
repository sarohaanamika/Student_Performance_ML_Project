## Student Performance Prediction
### Overview
This project is focused on predicting student performance in reading, writing, and math based on various factors like gender, parental level of education, test preparation course, etc. The prediction model is built using machine learning techniques and is hosted locally using Flask as a web application.

### Project Description
### Problem Statement:
The main goal is to predict student performance in terms of scores in reading, writing, and math based on several input features such as demographic and personal data, to identify patterns that impact academic performance.

### Objectives:
Preprocess and clean the dataset.
Develop machine learning models to predict students' scores.
Implement the prediction system using a Flask-based web application.
Technologies Used
Programming Language: Python
Framework: Flask
Libraries:
Machine Learning: Scikit-learn, Pandas, NumPy
Flask (for the web application)
CatBoost (used for boosting in ML)

## Project Structure 

ML_project_1/
├── .ebextensions/           # AWS Elastic Beanstalk configuration (optional)
├── python.config            # Python configuration for environment
├── artifacts/               # Directory for storing artifacts
├── catboost_info/           # CatBoost related files (training logs, etc.)
├── logs/                    # Logs generated during training and running
├── mlproject1.egg-info/     # Package information files
├── notebook/                # Jupyter notebooks (experiments, EDA, etc.)
├── src/
│   ├── pipeline/
│   │   ├── predict_pipeline.py  # Code for running predictions using the model
│   └── preprocessing.py    # Data preprocessing scripts
├── templates/               # HTML templates for the Flask web app
├── venv/                    # Python virtual environment files
├── .gitignore               # Git ignore file
├── app.py                   # Main Flask application
├── application.py           # Alternate Flask application (if any)
├── README.md                # Project documentation
├── requirements.txt         # Python dependencies
└── setup.py                 # Package setup script

### Set Up the Virtual Environment: Create a virtual environment to isolate dependencies:
python3 -m venv venv
source venv/bin/activate

### Install Required Packages: Install all the necessary dependencies by running:
pip install -r requirements.txt

### Run the Flask Application:
python app.py

### Access the Application: Open your web browser and go to:
http://127.0.0.1:5000

