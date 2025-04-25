# LOGISTIC-META-MODEL-LMM-ALGORITHM

This project focuses on detecting fraudulent credit card transactions using a **stacked ensemble model** that combines the predictive power of Logistic Regression, XGBoost, and Random Forest classifiers. The meta model used is **Logistic Regression**, offering robust and interpretable results. The model is deployed via a web application using **Flask** for the backend and **HTML/CSS/JavaScript** for the frontend.

## 🚀 Features

- Stacked ensemble model for enhanced fraud detection accuracy
- Logistic Regression as the meta-classifier
- Real-time fraud prediction with 30 input features
- User-friendly web interface
- Ready for future integration of advanced security features

## Why use stacking?

Stacked models are great for problems where:
The dataset is imbalanced or noisy
No single model performs well across all patterns
Combining diverse classifiers improves prediction reliability

## 🧠 Algorithms Used

- Random Forest Classifier
- XGBoost Classifier
- Logistic Regression (Base + Meta model)

## 📁 Files and Structure
fraud_detection_website/
│
├── stackinglogistic.ipynb          # Jupyter Notebook with model training and logic
├── app.py                          # Flask backend server
├── model.pkl                       # Trained stacked model (serialized)
├── scalar.pkl             
├── index.html                  # Frontend HTML page
├── style.css                   # CSS for styling the UI
│--- script.js                   # JavaScript for frontend logic


## 🔮 Future Enhancements

- Iris and fingerprint authentication
- OTP verification system
- Security questions module
- Automated credit card blocking bot on fraud detection

## 🛠️ Tech Stack

- Python, Flask
- HTML, CSS, JavaScript
- scikit-learn, XGBoost
- Jupyter Notebook

## 🧩 Broader Use Cases
While this project is built for credit card fraud detection, the stacked ensemble learning algorithm used here can be applied to a wide range of classification problems in various domains:
🩺 Medical Diagnosis:
Predict diseases such as cancer, diabetes, or heart conditions using patient data by combining multiple predictive models for better accuracy.
📊 Financial Risk Assessment:
Analyze loan applications, credit scoring, and detect insurance fraud by capturing diverse financial indicators through ensemble modeling.
🛍️ Customer Churn Prediction:
Identify customers likely to leave a service or product based on behavioral and transactional data.
🎓 Academic Performance Forecasting:
Predict student success or drop-out risk using academic records, attendance, and other performance metrics.
🔐 Cybersecurity Threat Detection:
Detect potential cyberattacks or malicious activity using network logs, user behavior, and traffic patterns.



