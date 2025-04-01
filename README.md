# Customer-Churn-Analysis-and-Prediction

![Customer Churn Prediction Accuracy](download(1).png)

## Overview
This project focuses on predicting customer churn using machine learning techniques. The goal is to analyze customer behavior and determine the likelihood of a customer leaving a service or subscription. The insights derived from this model can help businesses implement retention strategies.

## Features
- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Machine Learning model training and evaluation
- Model deployment (optional)

## Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn, Plotly
- Machine Learning Algorithms 

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/churn-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd churn-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Exploratory Data Analysis (EDA)
EDA was conducted to understand customer demographics and churn patterns:
- **Churn Distribution:** Approximately 26.6% of customers have churned.
- **Gender vs. Churn:** Male and female customers churn at similar rates.
- **Contract Type Impact:** Customers with month-to-month contracts churn more frequently than those with longer contracts.
- **Feature Correlation:** Total charges and tenure have a strong correlation with churn probability.
- **Visualizations:** Pie charts and heatmaps were used to analyze key insights.

## Model Training & Evaluation
Several machine learning models were trained and evaluated:
- **Algorithms Used:** Logistic Regression, Decision Tree, Random Forest, XGBoost, CatBoost, and others.
- **Evaluation Metrics Used:** Confusion Matrix, ROC-AUC, Precision, Recall, and F1-score.

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Load and run `Churn prediction.ipynb`.
3. Follow the steps inside the notebook to preprocess data, train models, and evaluate results.

## Dataset
The dataset used in this project consists of customer records, including features such as tenure, monthly charges, total charges, contract type, payment method, and more. Ensure you have the dataset in the appropriate location before running the notebook.

## Results
The trained model provides a probability score indicating the likelihood of customer churn. Evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess model performance.

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact
For any queries, reach out to suyashbargal@gmail.com.
