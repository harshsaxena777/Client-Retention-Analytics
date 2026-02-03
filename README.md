#Client Retention Analytics

📌 Project Overview
This project focuses on identifying patterns and predicting customer attrition (churn) for a service-based platform. By analyzing historical user data, demographic profiles, and engagement metrics, we build a predictive framework that helps businesses intervene before a customer decides to leave.

The goal is to move from reactive measures to proactive retention strategies using Machine Learning.

📊 Dataset Insights
The analysis is performed on a dataset containing diverse customer attributes, including:

Demographics: Age, gender, and geographical location.

Account Details: Tenure, contract type, and payment methods.

Usage Patterns: Monthly charges, total spend, and service subscriptions (Internet, Streaming, Support, etc.).

Target Variable: Churn (Yes/No) – indicating if the customer stopped using the service.

🛠️ Tech Stack
Language: Python 3.x

Data Manipulation: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly

Machine Learning: Scikit-learn, XGBoost, LightGBM

Environment: Jupyter Notebook / Google Colab

🚀 Key Workflow
Exploratory Data Analysis (EDA): Identifying correlations between contract types and churn rates. Visualizing how monthly charges impact customer loyalty.

Data Preprocessing: * Handling missing values and outliers.

Encoding categorical variables (One-Hot & Label Encoding).

Feature scaling to normalize numerical ranges.

Handling Class Imbalance: Utilizing techniques like SMOTE (Synthetic Minority Over-sampling Technique) to ensure the model doesn't overlook the minority "Churn" class.

Model Development: Training multiple classifiers including:

Logistic Regression (Baseline)

Random Forest

XGBoost Classifier

Evaluation: Comparing models based on Recall (to minimize false negatives) and F1-Score.

📈 Results & Findings
Key Drivers: Customers on "Month-to-month" contracts and those with higher monthly charges showed the highest propensity to churn.

Top Model: The XGBoost model achieved the best performance with accuracy and a high recall rate for churners.

📂 Project Structure
Plaintext
├── Data/                   # Raw and processed datasets
├── Notebooks/              # Jupyter notebooks for EDA and Modeling
├── Models/                 # Saved model weights (.pkl or .joblib)
├── README.md               # Project documentation
└── requirements.txt        # List of dependencies

⚙️ Installation
To run this project locally, follow these steps:

Clone the repository:
git clone https://github.com/harshsaxena777/Client-Retention-Analytics.git

Install dependencies:
pip install -r requirements.txt

Launch the notebook:
jupyter notebook

