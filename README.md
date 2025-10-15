📊 Telco Customer Churn Prediction
📌 Overview
Customer churn is a major challenge in the telecom industry, where retaining existing customers is often more cost-effective than acquiring new ones.

This project applies machine learning models to predict whether a customer will churn based on their demographic, account, and service details. By identifying churn-prone customers, telecom companies can take proactive measures to improve retention.

📂 Dataset
Source: 

Shape: 7,043 rows × 21 columns

Target Variable: Churn (Yes / No)

Features include:
Demographics: gender, senior citizen, partner, dependents

Account Info: tenure, contract type, payment method, monthly charges

Services: phone service, internet service, streaming, security options

⚙️ Workflow
Data Cleaning & Preprocessing

Handle missing values

Encode categorical variables (Label Encoding, OneHot Encoding)

Feature scaling (StandardScaler / MinMaxScaler)

Exploratory Data Analysis (EDA)

Visualized churn vs non-churn trends

Correlation analysis

Service and contract impact on churn

Modeling & Evaluation

Models: Logistic Regression, Random Forest, Gradient Boosting, XGBoost

Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

🧠 Technologies
Language: Python

Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

Environment: Jupyter Notebook

📊 Results
Best Model: XGBoost

Performance:

Accuracy: ~82%

ROC-AUC: ~0.85

Balanced Precision & Recall

🚀 Future Improvements
Advanced hyperparameter tuning

Feature selection for model optimization

Deployment via Streamlit / Flask

Dashboard for real-time churn prediction

🔧 Installation & Usage
# Clone this repository
git clone https://github.com/your-username/telco-churn-prediction.git

# Navigate to the project folder
cd telco-churn-prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
🤝 Author
👩‍💻 Mangaiyarkarasi Chandrasekar

🔗 LinkedIn

🐙 GitHub

✨ This project highlights how machine learning can help businesses reduce customer churn and improve long-term profitability.
