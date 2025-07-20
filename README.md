ChurnGuard AI : Predict, Prevent, Prosper
The Problem: Why Churn Matters
Customer churn is a silent revenue killer. Businesses invest heavily in acquiring customers, only to lose them due to factors like poor service, better competitor offers, or lack of engagement. The challenge lies in identifying at-risk customers before they leave. Traditional approaches rely on historical data and manual analysis, which are time-consuming and often ineffective. Without a proactive solution, businesses are left playing catch-up, losing valuable customers and revenue in the process.

Solution
This application uses a TensorFlow deep learning model trained on historical customer data to predict churn probability. Key components include:

User-Friendly Interface: Built with Streamlit, the GUI allows users to input customer demographics, financial metrics, and engagement details.

Automated Preprocessing: Integrates label encoding, one-hot encoding, and feature scaling to replicate training-phase transformations.

Real-Time Insights: Outputs a churn probability score (0–1) and a binary classification (likely/unlikely to churn).

Impact
Retention Optimization: Identifies high-risk customers early, enabling personalized retention efforts.

Cost Reduction: Lowers customer acquisition costs by prioritizing retention of existing clients.

Data-Driven Strategy: Supports decision-making with transparent, ML-powered predictions.

Usages
Input customer details (e.g., geography, age, credit score) using dropdown menus, sliders, and number fields.

Click Predict Churn to generate results.

Interpret the output:

Churn Probability: A numerical score between 0 and 1.

Classification: A binary prediction ("likely" or "unlikely" to churn).

Installation Guide
Prerequisites
Python 3.7 or higher

pip package manager

Steps To Run Locally
Clone the Repository:
   git clone https://github.com/your-repo/customer-churn-prediction.git  
   cd customer-churn-prediction  
Create a Virtual Environment (recommended for dependency isolation):
   python -m venv venv  
   source venv/bin/activate  # For Windows: venv\Scripts\activate  
Install Dependencies:
   pip install -r requirements.txt  
Place the following files in the Models/ directory:
Final_model.h5 (pre-trained TensorFlow model)

label_encoder_gender.pkl, onehot_encoder_geo.pkl, scaler.pkl (preprocessing pipelines)

Launch the Application:
   git clone https://github.com/your-repo/customer-churn-prediction.git  
   cd customer-churn-prediction  
   Create a Virtual Environment (recommended for dependency isolation):
Note: Replace your-repo in the clone command with your repository URL. Ensure model and preprocessing files are available in the Models/ directory before running the app.
Authors
