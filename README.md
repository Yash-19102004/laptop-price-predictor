# laptop-price-predictor
This code builds and deploys a laptop price prediction model using Streamlit for a user-friendly interface. Here's a brief overview:

Data Loading and Preprocessing:
The laptop dataset is loaded and cleaned by removing unwanted columns and converting RAM and weight to numeric values.

Feature and Target Separation:
Features (X) and target (y) are separated, followed by splitting the data into training and testing sets.

Preprocessing Setup:
Categorical and numerical features are defined and preprocessed using ColumnTransformer and Pipeline

Model Training:
A linear regression model pipeline is created and trained on the training data.

Model Saving:
The trained model is saved to a file using joblib.

Streamlit App:
A web app interface is built using Streamlit to allow users to input laptop details and get a price prediction.
User inputs are collected via dropdowns and number inputs.
When the "Predict Price" button is clicked, the model predicts and displays the laptop price.
This setup integrates data preprocessing, model training, and a web-based interface for practical and interactive price predictions.
