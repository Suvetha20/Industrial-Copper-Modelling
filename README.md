# Industria Copper Modelling
## Introduction
  This project aims to develop two machine learning models for the copper industry to address the challenges of predicting selling price and lead classification. Manual predictions can be time-consuming and may not result in optimal pricing decisions or accurately capture leads. The models utilize advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format, identifying the distribution of features, and leveraging tree-based models, specifically the decision tree algorithm, to predict the selling price and leads accurately.

## Features

  * Predict Selling Price: Using input parameters, predict the selling price of copper.
    
  * Predict Status: Determine whether a lead is likely to be won or lost.

## Technologies Used

  * Python
    
  * Pandas
    
  * Data Preprocessing
    
  * Exploratory Data Analysis (EDA)
    
  * Scikit-learn
    
  * Streamlit
    
## Installation

  * Clone the repository
  
  * Install the required packages
  
  * Run the Streamlit application

## Usage

 1.Load Data: Ensure the copper.csv file is in the root directory of the project.

 2.Prepare Models: The project relies on pre-trained models saved as model.pkl, scaler.pkl, t.pkl, s.pkl, cmodel.pkl, cscaler.pkl, and ct.pkl. These should be 
   placed in the root directory as well.

 3.Run the App: Start the Streamlit app by running streamlit run app.py. Navigate to the provided URL to interact with the application.

 4.Navigate Tabs: Use the tabs in the application to switch between:

  * Home
    
  * Predict Selling Price
    
  * Predict Status
    
## Predict Selling Price

  * Inputs: Quantity in tons, thickness, width, customer ID, and other features.

  * Output: Predicted selling price.

## Predict Status

  * Inputs: Quantity in tons, thickness, width, customer ID, selling price, and other features.
    
  * Output: Predicted lead status (Won/Lost).

## Code Structure

  * app.py: Main file to run the Streamlit app.
    
  * models/: Directory to store pre-trained model files.
    
  * data/: Directory to store data files.
    
  * requirements.txt: List of Python packages required to run the application.
