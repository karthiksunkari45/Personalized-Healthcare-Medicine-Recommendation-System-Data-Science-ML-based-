PERSONALIZED HEALTHCARE & MEDICINE RECOMMENDATION SYSTEM
===============================================================

INPUT
- Cleaned_Dataset.csv supplied by the user
- Rows: 349
- Columns: 14

MODEL
- Target: risk_level
- Algorithm: Random Forest Classifier (300 trees)
- Categorical: one-hot encoding
- Numeric: standard scaling
- Train/test split: 80/20, stratified, random_state=42
- Test accuracy on this split: 0.7857

OUTPUT FILES
- Healthcare_ML_Final_Output.csv : row-level predictions and confidence
- Healthcare_Project_KPIs.csv : project KPI summary
- Healthcare_Disease_Summary.csv : Power BI-ready disease summary
- Healthcare_Dashboard.html : interactive dashboard
- healthcare_risk_model.joblib : trained model
- Healthcare_Project_Readme.txt : project notes

MEDICINE RECOMMENDATION NOTE
The supplied dataset has no medication/drug column or treatment mapping.
Therefore no drug recommendation was fabricated. A production medicine module
should use a clinician-validated medication knowledge base and safety checks
(allergies, interactions, contraindications, age/pregnancy, dosage, etc.).
