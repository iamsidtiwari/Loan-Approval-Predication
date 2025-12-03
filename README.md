 Loan Approval Prediction System

A machine learning + Flask based web app that predicts whether a loan application will be **Approved** or **Rejected** based on applicant financial data.

---

 Features
- Random Forest–based ML model  
- Clean preprocessing (encoding + scaling)  
- Handles unseen labels safely  
- User-friendly Flask web interface  
- Trained model + encoders saved for reuse  

---

 Installation

```bash
pip install -r requirements.txt

Train the Model

python train.py
This generates:

loan_model.pkl

scaler.pkl

label_encoders.pkl

feature_names.pkl

Run the Web App
python app/app.py


Open in browser:
 http://localhost:5000/
What the App Does

Takes user financial inputs

Encodes & scales them

Predicts loan status

Shows confidence score

