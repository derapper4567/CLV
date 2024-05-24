CUSTOMER LIFETIME VALUE PROJECT
Goals: tends to understand which customers to focus on prediction task by answering How much will spend in future , what probability will they make another purchase in the future.
      ⚡ Which customers have highest spend probability in next 90 days.
      ⚡ Which customers have recently purchased but unlikely to buy.
      ⚡ Which customers were predicted to purchase but didn't(missed opportunities)


This project aims to predict the Customer Lifetime Value (CLV) using Python and integrate the prediction model into a Shiny web application. The CLV prediction model will enable
businesses to forecast the future value of their customers and make data-driven decisions to improve customer retention and loyalty.


⚡FEATURE
Python script for training and deploying the CLV prediction model, Shiny web application for visualizing and interacting with the prediction results
Input data in YAML format for easy configuration and customization

⚡Usage
Prerequisites
Python 3.8 
Dash package
YAML Python library

 👯Installation
Clone the repository:
git clone https://github.com/CLV/clv-prediction-project.git

Install the required Python libraries:
pip install pandas scikit-learn

Install the Shiny package in python:
install.packages('dash')

Training the Model
Update the config.yaml file with the necessary parameters such as data file path, model hyperparameters, etc.

Run the Python script to train the CLV prediction model:
python train_model.py

Deploying the Web App

Update the config.yaml file with the model path and other configurations required for the web application.
Run the dash web application:

Configuration (config.yaml)
The config.yaml file contains the configurations for training the model and running the Shiny web application. Modify this file according to your requirements.
