# customer_churn-SyriaTel
Phase 3 Moringa School Project, to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company. 
Project Title: SyriaTel Customer Churn Prediction
Project Overview
The aim of this project is to build a machine learning classifier to predict whether a customer will "soon" stop doing business with SyriaTel, a telecommunications company. This is a binary classification problem where the goal is to identify the likelihood of customer churn.

Stakeholders: The primary stakeholders are the management team at SyriaTel, who are interested in reducing customer churn rates. By identifying customers who are likely to churn, the company can proactively take measures to retain them, thereby minimizing revenue loss.

Business Problem: The telecommunications industry often faces high rates of customer churn. Retaining customers is more cost-effective than acquiring new ones. Thus, predicting churn allows SyriaTel to devise targeted retention strategies.

Dataset Information
The dataset used in this project is sourced from SyriaTel, containing various features that provide insights into customer demographics, account information, and usage patterns.

Data Source: The dataset is anonymized and comprises customer behavior data related to their interactions with SyriaTel's services.

Key Features:

Customer Account Information: This includes features such as tenure (how long a customer has been with SyriaTel), contract type (e.g., month-to-month, one year, two years), payment method, etc.
Usage Data: Features such as monthly charges, total charges, and various service usage metrics are included.
Demographic Data: Gender, whether a customer is a senior citizen, and whether they have a partner or dependents.
Project Structure
index_updated.ipynb: The main Jupyter Notebook containing the data analysis, feature engineering, model training, evaluation, and results.
data/: Directory containing the dataset used for analysis.
images/: Directory for storing plots and visualizations used in the project.
Installation and Requirements
To run this project, you'll need Python and several libraries.
Methodology

Data Preprocessing:

Data was cleaned and prepared for modeling, including handling missing values, encoding categorical variables, and scaling numerical features.
Modeling:

Multiple classification algorithms were explored, including Logistic Regression, Decision Trees, and Random Forests.
Models were trained on the training set and evaluated on the test set using appropriate metrics.

Evaluation:

The models were evaluated based on metrics such as Accuracy, Precision, Recall, F1 Score, and ROC-AUC to determine their effectiveness in predicting churn.
Results and Findings
The Random Forest model provided the best performance with an overall accuracy of 91% , and the ROC AUC score of 0.93.
Key features influencing customer churn included tenure, monthly charges, and contract type.

Conclusions and Recommendations
The predictive model developed can help SyriaTel identify high-risk customers and take proactive measures to retain them. It is recommended that SyriaTel focuses on customers with specific contract types and monthly charges, as these are significant predictors of churn.

Contributors
Camilla Lumwaji (lumwajicamilla1@gmail.com)
