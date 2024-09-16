# Loan Eligibility Prediction System

This repository contains a **Loan Eligibility Prediction System** built using **Python**, **Flask**, and **Pickle** for model deployment. The system predicts whether a user is eligible for a loan based on various input features such as credit score, income, loan amount, employment status, etc. 

## Features
- **Loan Eligibility Prediction**: Predicts whether a user is eligible for a loan based on factors such as income, employment status, credit score, and more.
- **Flask Web Interface**: A user-friendly web interface built using Flask that accepts input from the user and displays the prediction results.
- **Model Deployment**: A pre-trained machine learning model serialized using **Pickle** is used to perform real-time predictions.
- **Custom Frontend**: HTML based interface with static resources (images) in the `static` folder.

## Project Structure

```bash
loan-eligibility-prediction/
│
├── app.py                  # Flask application entry point
├── model.pkl               # Pickle file for the trained machine learning model
├── templates/              # Folder containing HTML templates
│   └── index.html          # Main HTML file for user input form 
├── static                  # Folder for static files (images used)
└── README.md               # Project documentation
```
## Technologies Used
- Python: Backend language for machine learning and web development.
- Flask: Web framework for creating the web interface.
- Pickle: For serializing and deserializing machine learning models.
- scikit-learn: Used for building and training the machine learning model.
- Pandas and NumPy: For data manipulation and analysis.
- HTML: For designing the frontend interface (located in the templates folder).
