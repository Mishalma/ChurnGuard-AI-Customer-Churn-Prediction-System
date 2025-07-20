# ChurnGuard AI — Predict, Prevent, Prosper 🚀

**ChurnGuard AI** is an intelligent customer churn prediction system designed to help businesses retain valuable clients and reduce revenue loss. Using a deep learning model built with TensorFlow and an interactive Streamlit interface, it enables real-time churn probability scoring with actionable insights.

---

## 🧠 The Problem: Why Churn Matters

Customer churn is a silent revenue killer. Businesses invest heavily in acquiring customers, only to lose them due to:
- Poor service
- Better competitor offers
- Lack of engagement

Traditional churn detection methods are reactive, slow, and manually intensive. Without predictive tools, businesses lose valuable customers and profit before they can act.

---

## ✅ The Solution

**ChurnGuard AI** provides a proactive, AI-powered solution to predict customer churn before it happens.

### 🔧 Core Features
- **Deep Learning Model**: Trained with TensorFlow on historical customer data.
- **Streamlit GUI**: Interactive dashboard for data input and real-time prediction.
- **Automated Preprocessing**: Includes label encoding, one-hot encoding, and feature scaling to match training-phase transformations.
- **Churn Insights**:
  - **Churn Probability**: A value between 0 and 1.
  - **Classification**: Predicts "Likely to Churn" or "Unlikely to Churn".

---

## 🎯 Impact

- 📊 **Retention Optimization**: Identify high-risk customers early.
- 💸 **Cost Reduction**: Minimize acquisition cost by focusing on existing clients.
- 🧩 **Data-Driven Strategy**: Support smarter decisions with transparent ML outputs.

---

## 🧪 Usage Instructions

1. Open the app and fill in customer details such as:
   - Geography
   - Gender
   - Age
   - Credit Score
   - Tenure
   - Balance
   - Estimated Salary
   - Number of Products
   - Is Active Member
2. Click the **"Predict Churn"** button.
3. Review the output:
   - **Churn Probability**: Numerical score (0 to 1)
   - **Classification**: "Likely" or "Unlikely" to churn

---

## 🛠️ Installation Guide

### 📋 Prerequisites
- Python 3.7+
- `pip` (Python package manager)

### 🚀 Steps to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/your-repo/customer-churn-prediction.git
cd customer-churn-prediction

# 2. (Optional but Recommended) Create and activate a virtual environment
python -m venv venv
# For macOS/Linux:
source venv/bin/activate
# For Windows:
venv\Scripts\activate

# 3. Install required packages
pip install -r requirements.txt

# 4. Place the required model and preprocessing files in the `Models/` directory:
#    - Final_model.h5
#    - label_encoder_gender.pkl
#    - onehot_encoder_geo.pkl
#    - scaler.pkl

# 5. Launch the Streamlit app
streamlit run app.py
