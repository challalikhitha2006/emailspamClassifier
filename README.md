# Email Spam Classifier

This project involves building a machine learning model to classify emails as spam or not spam. The model is trained using a dataset from Kaggle and is implemented in a Jupyter Notebook using Logistic Regression. Additionally, a Flask API is provided for interfacing with the trained model to classify emails. The API can be accessed locally by running the Flask server or through the hosted version 

## Dataset 

The dataset used for training the model is sourced from [Kaggle](https://www.kaggle.com/datasets/jackksoncsie/spam-email-dataset?resource=download) and can be found in `datasets/emails.csv`. The model, trained on this dataset, achieves an accuracy of 98.34% on the test data.

<div align="center">

![image](https://github.com/user-attachments/assets/1351fe99-8061-42b8-8ee8-87d4cc907ae5)

</div>

## Technologies Used

- **Python:** The core programming language used to develop the machine learning model and the Flask API.
- **Jupyter Notebook:** Used for implementing and testing the machine learning model.
- **Flask:** A lightweight WSGI web application framework used to create the API.
- **scikit-learn:** The machine learning library used to build and train the logistic regression model.
- **matplotlib**: A plotting library used for visualizing data and model performance.
- **pandas**: A data manipulation and analysis library used for handling datasets, including loading, cleaning, and preprocessing data.
- **numpy**: A library for numerical computations, used for handling arrays and performing mathematical operations.

## Project Structure

- `EmailSpamClassifier.ipynb`: Jupyter Notebook containing the implementation of the spam classifier model.
- `models/`: Directory where the trained model and feature extractor are saved.
- `datasets/`: Directory where the datasets are stored.
- `app.py`: Flask API for interfacing with the trained model.
- `requirements.txt`: Python package dependencies.






