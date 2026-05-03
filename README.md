🏥 Hospital Readmission Prediction for Diabetic Patients
Advanced Health Informatics & Machine Learning Project
📝 Project Overview
This project focuses on predicting hospital readmission for diabetic patients within 30 days of discharge. Using a real-world dataset from 130 US hospitals (1999–2008), I developed a Machine Learning model to identify high-risk patients, helping healthcare providers improve patient care and reduce costs.
🛠️ Key Technical Steps
• Data Cleaning: Handled missing values (represented as ?) and removed irrelevant features like weight (90% missing) and administrative IDs.
• Feature Engineering: Converted the target variable readmitted into a binary format (1 for <30 days, 0 otherwise) for precise clinical prediction.
• Model Training: Implemented a Random Forest Classifier to handle complex medical data patterns.
• Evaluation: Achieved an accuracy of 88%.
📊 Insights & Discovery
The model revealed that number_inpatient (the number of previous hospital visits) is the strongest predictor of future readmission. This insight allows hospitals to prioritize preventive care for frequently hospitalized patients.
🚀 Future Roadmap (AWS Deployment)
The next phase involves deploying this model using Amazon SageMaker and AWS S3 to create a real-time prediction API for clinical use
