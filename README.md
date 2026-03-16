# Employee Salary Prediction

## Overview
This project builds a Machine Learning model to predict employee salary levels based on factors such as age, education, occupation, gender, and hours worked per week. The model is trained using a Random Forest Classifier and deployed through a simple Streamlit web application that allows users to input details and get salary predictions.

## Features
- Data preprocessing and feature selection
- Encoding categorical variables using LabelEncoder
- Training a Random Forest machine learning model
- Model evaluation using train-test split
- Interactive web interface built with Streamlit
- Model saving and loading using Joblib

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Joblib

## Project Structure
```
employee_salary_prediction
│
├── app.py              # Streamlit web application
├── train_model.py      # Script to train the machine learning model
├── model.py            # Model training and saving logic
├── income_model.pkl    # Trained model file
├── encoders.pkl        # Saved label encoders
├── salary_data.csv     # Dataset used for training
└── README.md           # Project documentation
```

## How to Run the Project

### 1. Clone the Repository
```
git clone https://github.com/rajanandini1224/employee_salary_prediction.git
cd employee_salary_prediction
```

### 2. Install Required Libraries
```
pip install pandas numpy scikit-learn streamlit joblib
```

### 3. Train the Model
```
python train_model.py
```

### 4. Run the Streamlit Application
```
streamlit run app.py
```

## Example Input Features
- Age
- Education
- Occupation
- Gender
- Hours per week

The application predicts whether the employee salary is above or below a certain income level.

## Future Improvements
- Add more features for better prediction accuracy
- Improve model performance with advanced algorithms
- Deploy the application on cloud platforms

## Author
Rajanandini Godisela
