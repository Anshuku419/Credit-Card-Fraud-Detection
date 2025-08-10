# Credit-Card-Fraud-Detection
This project implements a Machine Learning model to detect fraudulent credit card transactions with 99.1% accuracy. It uses advanced feature engineering, data preprocessing, and ensemble methods to handle the highly imbalanced nature of fraud datasets. The model is trained and evaluated using real-world credit card transaction data.

# 📌 Features
Data Preprocessing – Handles missing values, normalizes data, and encodes categorical features.
Imbalanced Data Handling – Uses SMOTE (Synthetic Minority Oversampling Technique) to improve model performance.
Feature Engineering – Selects the most relevant features for fraud detection.
Model Training – Implements advanced algorithms such as XGBoost, Random Forest, and Logistic Regression.
Model Evaluation – Uses Accuracy, Precision, Recall, F1-Score, and ROC-AUC Score for performance metrics.
Visualization – Plots fraud vs non-fraud distributions and model performance graphs.

# 📂 Dataset
The dataset used in this project is the Credit Card Fraud Detection Dataset from Kaggle.
Number of Transactions: 284,807
Fraud Cases: 492 (0.172%)
Non-Fraud Cases: 284,315 (99.828%)

# 🛠️ Tech Stack
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, imbalanced-learn
Tools: Jupyter Notebook

# 🚀 Installation & Usage
Clone the Repository
bash
Copy
Edit
git clone https://github.com/Anshuku419/credit-card-fraud-detection.git
cd credit-card-fraud-detection
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook

bash
Copy
Edit
jupyter notebook Credit_Card_Fraud_Detection.ipynb
Run Predictions
Update the predict() function in the notebook to test new transaction data.

# 📊 Model Performance
Metric	Value
Accuracy	99.1%
Precision	98.9%
Recall	96.7%
F1-Score	97.8%
ROC-AUC	99.5%

# 📈 Visualizations
Fraud vs Non-Fraud Distribution
Correlation Heatmap
ROC Curve
Precision-Recall Curve

