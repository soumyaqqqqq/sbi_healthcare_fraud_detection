Healthcare Fraud Detection System

Overview

Healthcare Fraud Detection System is a machine learning-based application designed to identify suspicious insurance claims by comparing actual billing amounts with predicted values. The system automates document processing, data extraction, and anomaly detection to reduce manual verification efforts.

Features

* Automated PDF claim document processing
* OCR-based text extraction for scanned documents
* Extraction of hospital, doctor, and billing information
* Billing amount prediction using Random Forest Regression
* Fraud detection through anomaly analysis
* Flask-based web interface for claim submission and evaluation

Tech Stack

* Python
* Flask
* Scikit-learn
* Pandas
* NumPy
* PDFPlumber
* Tesseract OCR
* pdf2image
* Joblib

Workflow

1. Upload an insurance claim PDF.
2. Extract claim details using PDF parsing and OCR.
3. Process and encode relevant features.
4. Predict expected billing amount using the trained model.
5. Compare actual and predicted amounts.
6. Flag potentially fraudulent claims based on billing discrepancies.

Model

* Algorithm: Random Forest Regressor
* Features:
    * Doctor
    * Hospital
    * Medical Condition
    * Admission Type
    * Insurance Provider
* Evaluation Metric: Mean Absolute Error (MAE)

Impact

* Reduced manual claim verification effort through automation.
* Enabled rapid processing of insurance claim documents.
* Improved efficiency of fraud screening using machine learning and anomaly detection.

Future Improvements

* Integration of deep learning-based fraud detection models.
* Real-time claim monitoring dashboard.
* Explainable AI for fraud prediction decisions.
* Support for additional healthcare document formats.
