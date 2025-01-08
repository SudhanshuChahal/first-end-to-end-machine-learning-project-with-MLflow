# first-end-to-end-machine-learning-project-with-MLflow


## Workflow

1. update config.yaml
2. update schema.yaml
3. update params.yaml
4. update the entity
5. update the configuration manager in src config
6. update the components 
7. update the pipeline
8. update the main.py
9. update the app.py



# How to run?

### STEPS:

Clone the repository

'''bash
https://github.com/SudhanshuChahal/first-end-to-end-machine-learning-project-with-MLflow

### STEP 01- Create  conda environment after opening the repository

'''bash 
conda create -n mlproj python 3.11.4 -y 

'''bash 
conda activate mlproj
'''


### STEP 02- install the requirements
'''bash
pip install -r requirements.txt
'''


'''bash
# Finally run the following command 
python app.py
'''

Now, 
''' bash
open up your local host and port 
'''



## MLflow

[Documentation] (https://mlflow.org/docs/latest/index.html)


#### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI =https://dagshub.com/sudhanshuchahal262/first-end-to-end-machine-learning-project-with-MLflow.mlflow
MLFLOW_TRACKING_USERNAME =sudhanshuchahal262 
MLFLOW_TRACKING_PASSWORD=fa43d06bf6f1d1a89b06b77537418f2c918919f7
python script.py

Run this to export as env variables:

''' bash

export $env:MLFLOW_TRACKING_URI=https://dagshub.com/sudhanshuchahal262/first-end-to-end-machine-learning-project-with-MLflow.mlflow

export $env:MLFLOW_TRACKING_USERNAME="sudhanshuchahal262" 

export "$env:MLFLOW_TRACKING_PASSWORD="fa43d06bf6f1d1a89b06b77537418f2c918919f7"


# AWS-CICD-Deployment-with-Github-Actions

### 1.Login to AWS console.

### 2.Create IAM user for deployment

### 3.Create ECR repo to store/save docker image

### 4.Create EC2 machine(Ubuntu)