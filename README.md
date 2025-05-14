# Diabetes-Prediction
Diabetes Prediction
🩺 Diabetes Prediction Web App
A machine learning-powered web application that predicts the likelihood of diabetes in a patient based on health parameters such as glucose level, BMI, insulin level, and more.

<div align="center"> <img src="https://img.shields.io/badge/Python-3.9-blue?logo=python" /> <img src="https://img.shields.io/badge/Flask-WebApp-lightgrey?logo=flask" /> <img src="https://img.shields.io/badge/ML-Model%20Based-orange?logo=scikit-learn" /> </div>
🚀 Project Overview
This web app uses a trained Random Forest Classifier to predict whether a patient is likely to have diabetes. Built using Flask, the app takes 8 health metrics as input and displays the prediction result in an intuitive interface.

🔬 Features
✅ Input health data (Pregnancies, Glucose, Blood Pressure, BMI, etc.)

✅ Predict diabetes risk instantly

✅ Clean and user-friendly interface

✅ Trained on Kaggle's Pima Indians Diabetes dataset

✅ Deploy-ready with pre-trained model in pickle format

🧠 Model Details
Dataset: Kaggle Diabetes Dataset

Algorithm: Random Forest Classifier

Preprocessing:

Handled missing values in critical columns (Glucose, BP, BMI, etc.)

Imputation with mean/median depending on distribution

Train/Test Split: 80% Train / 20% Test

🛠 How to Run the App Locally
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/diabetes-prediction-flask.git
cd diabetes-prediction-flask
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Run the Flask App

bash
Copy code
python app.py
Open in Browser

Visit http://127.0.0.1:5000/

📁 File Structure
csharp
Copy code
.
├── app.py                      # Flask application
├── diabetes-prediction-rfc-model.pkl  # Trained ML model
├── templates/
│   ├── index.html              # Input form page
│   └── result.html             # Result display page
├── static/                     # CSS/Images (if any)
└── dataset/
    └── kaggle_diabetes.csv     # Training dataset
🧪 Sample Inputs
Feature	Example Value
Pregnancies	2
Glucose	120
Blood Pressure	70
Skin Thickness	25
Insulin	100
BMI	28.7
Diabetes Pedigree Function (DPF)	0.45
Age	30

📊 Example Prediction
Input: Glucose = 145, BMI = 33.6, Age = 50
Prediction: 🔴 High Risk of Diabetes

🤝 Contributing
Pull requests are welcome! If you find a bug or want to add new features, feel free to open an issue or PR.

📃 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Kaggle Pima Indians Dataset

Scikit-Learn

Flask

Created with 💙 by [Vedanth]
