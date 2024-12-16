# CS668 Optimizing Bank Marketing Strategies through Predictive Analytics and Customer Segmentation
Venkata Ram Pranith Garlapati

● This work was realized as part of the capstone project of the MS in Data Science at Pace University.

# Abstract 

The project deals with optimizing bank marketing strategies from predictive analytics and customer segmentation. Employing machine learning models, this study identifies crucial factors affecting customers' willingness to subscribe to term deposits and increases targeting efficiency in telemarketing campaigns. Ensemble models, including XGBoost and Random Forest, were applied to predict customer behavior with good performance. Model outputs were interpreted by means of a SHAP analysis, with insightful recommendations to marketing managers. Results show that call duration, contact type, and previous campaign outcomes have substantial impacts on conversion rates. The study illustrates how advanced predictive models can improve marketing efficiencies, shave costs, and help in increasing customer conversions.

# Table of Contents

●	Overview

●	Motivation

●	Data Description

●	Approach and Methodology

●	Results

●	Limitations

●	Installation

●	Usage

●	Contributing

●	License

# Motivation

The primary goal is to understand the key features influencing customer conversions during telemarketing campaigns, identify the best-performing predictive models, and derive actionable insights to enhance marketing efficiency. This project contributes to improving customer targeting, optimizing conversion rates, and minimizing costs.
 
# Data Description

The dataset used in this project is the "Bank Marketing" dataset from the UCI Machine Learning Repository. It includes client demographic information, historical campaign outcomes, and other relevant features.

https://github.com/Pranithgarlapati17/cs668/raw/edf93c42169bc666d07d797da54fafde165b9c0e/Banking%20data.xlsx

# Key Features Include:

●	Age: Client's age

●	Job: Job type (e.g., "admin", "technician")

●	Marital: Marital status (e.g., "married", "single")

●	Education: Education level (e.g., "primary", "secondary")

●	Balance: Yearly account balance in euros

●	Contact: Contact type (e.g., "telephone", "cellular")

# Target Variable:

●	Subscription to Term Deposit ("yes"/"no")

# Approach and Methodology

1.	Exploratory Data Analysis (EDA): We conducted EDA to explore customer demographics, account balances, and campaign outcomes.

2.	Feature Engineering: Relevant variables were selected through feature selection techniques, including age, occupation, and campaign outcomes.
Interaction features were created to improve model performance.

3.	Model Selection: We applied several machine learning models:Logistic Regression (Baseline),Decision Tree,Random Forest,Gradient Boosting,XGBoost (Advanced)

4.	Cross-validation was used to ensure model generalization and prevent
overfitting.
 
5.	Evaluation Metrics: Models were evaluated based on metrics like accuracy, precision, recall, F1-score, and Area Under Curve (AUC). SHAP values
were used for model interpretability.

# code

https://github.com/Pranithgarlapati17/cs668/blob/aac2572769960aa3bee1825a0f18f527cc8abc53/final%20code%20(pranith).ipynb

# Results

●	Best Model: XGBoost achieved the highest AUC score (0.72) and demonstrated superior balance between precision and recall.

●	Key Features: Duration, contact type, and previous campaign outcomes were the most impactful features for predicting customer conversion.

●	Actionable Insights: Increased call duration and targeting customers without housing loans were effective strategies for boosting conversion
rates.

# Limitations

●	Data Imbalance: The dataset had an imbalance in target classes, affecting recall for minority classes.

●	Feature Limitations: The limited number of features restricted model accuracy. Additional features, such as customer satisfaction ratings, could
further enhance predictions.

●	Computational Constraints: Insufficient resources limited exhaustive hyperparameter tuning.

# Poster
https://github.com/Pranithgarlapati17/cs668/blob/aac2572769960aa3bee1825a0f18f527cc8abc53/Poster%20.pdf
![image](https://github.com/user-attachments/assets/baed5670-a14a-4319-a192-ef58139178a9)

