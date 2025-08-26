
# 🏥 Medical Insurance Fraud Detection System Using Python

This project aims to detect fraudulent medical insurance claims using machine learning techniques. It helps insurance companies reduce financial losses and improve claim processing efficiency.

---

## 📦 Project Structure

- `data/`: Contains raw and processed claim datasets
- `notebooks/`: Jupyter notebooks for EDA and model training
- `models/`: Saved ML models (`.pkl` files)
- `app/`: Flask web application for deployment
- `README.md`: Project overview and documentation

---

## 📊 Data Pipeline

### 1. Data Collection
- Patient demographics
- Diagnosis and procedure codes
- Billing amounts
- Provider details

### 2. Data Preprocessing
- Missing value handling
- Feature engineering (e.g., claim frequency, avg billing)
- Encoding categorical variables
- Scaling numerical features

### 3. Exploratory Data Analysis (EDA)
- Distribution plots
- Correlation heatmaps
- Outlier detection

---

## 🤖 Machine Learning Models

| Model              | Description                                  |
|-------------------|----------------------------------------------|
| **XGBoost**        | High-performance gradient boosting           |
| **SVM**            | Classifies claims as fraudulent or not       |
| **Random Forest**  | Robust ensemble method                       |
| **Logistic Regression** | Baseline binary classifier             |

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score

---

## 🧠 Optimization Techniques

- `GridSearchCV` for hyperparameter tuning
- `Cross-validation` for generalization

---

## 🌐 Deployment

- Built with **Flask**
- Upload claims via web interface
- View fraud predictions and analytics
- Models loaded from `.pkl` files for fast inference

---

## 🔍 Insights

- Fraud often originates from providers (e.g., upcoding)
- Post-payment detection is critical
- Balance between accuracy and speed is essential

---

## 📚 References

- [Kaggle Datasets](https://www.kaggle.com/)
- [GitHub Example Project](https://github.com/Nayansai/Fraud-Detection-In-Medical-Insurance-Claim-System-Using-Machine-Learning)

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/medical-insurance-fraud-detection.git

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app/app.py
