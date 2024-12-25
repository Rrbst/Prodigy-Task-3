Name: Rashmi Rekha Behera

Company:  PRODIGY INFOTECH

CIN: PIT/DEC24/02450

Domain: DATA SCIENCE

Duration: 1ST December2024 to 31st December2024

Overview of the Project

PROJECT : Predicting Customer Purchases Using a Decision Tree Classifier

Objective
The primary goal of this project is to develop a decision tree classifier that predicts whether a customer will purchase a product or service based on their demographic and behavioral data. By analyzing factors like age, income, education level, and previous marketing interactions, the model will provide insights into customer behavior and assist in targeted marketing strategies.

Dataset: Bank Marketing Dataset
Source: UCI Machine Learning Repository
Features:
Demographic data: Age, job, marital status, education.
Behavioral data: Contact type, number of previous campaigns, previous outcomes.
Target variable: y (binary: "yes" = customer purchased, "no" = customer did not purchase).
Steps Involved
Data Collection and Understanding:

Load the Bank Marketing dataset.
Inspect the dataset to understand the structure, features, and target variable.
Data Cleaning and Preprocessing:

Handle missing values, if any.
Encode categorical variables using label encoding or one-hot encoding.
Normalize or standardize numerical features if required.
Feature Selection:

Analyze correlations and feature importance.
Retain relevant features that influence the target variable.
Model Development:

Split the data into training and testing sets.
Train a decision tree classifier using the training data.
Tune hyperparameters such as tree depth, minimum samples per split, and criterion (e.g., Gini impurity or entropy).
Model Evaluation:

Evaluate the model on the test set using metrics like accuracy, precision, recall, F1-score, and ROC-AUC score.
Visualize the decision tree for interpretability.
Insights and Interpretation:

Identify key factors influencing customer decisions (e.g., education level, contact method).
Provide actionable recommendations for marketing strategies.
Tools and Libraries
Python: For programming.
Pandas and NumPy: For data manipulation and analysis.
Scikit-learn: For implementing the decision tree classifier.
Matplotlib and Seaborn: For visualizing results and the decision tree.
Deliverables
Data Preprocessing Report: Steps taken to prepare the data for analysis.
Model Summary: Details of the decision tree classifier and its performance.
Visualizations: Graphical representation of the decision tree and evaluation metrics.
Business Insights: Recommendations based on model findings.
Applications
Predictive modeling for customer behavior analysis.
Personalized marketing campaigns targeting high-probability customers.
Business decision-making and customer segmentation.
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 74681 entries, 0 to 74680
Data columns (total 4 columns):
 #   Column                                                 Non-Null Count  Dtype 
---  ------                                                 --------------  ----- 
 0   2401                                                   74681 non-null  int64 
 1   Borderlands                                            74681 non-null  object
 2   Positive                                               74681 non-null  object
 3   im getting on borderlands and i will murder you all ,  73995 non-null  object
dtypes: int64(1), object(3)
memory usage: 2.3+ MB
Training Data Info:
 None






File loaded successfully.

Dataset Info:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 74681 entries, 0 to 74680
Data columns (total 4 columns):
 #   Column                                                 Non-Null Count  Dtype 
---  ------                                                 --------------  ----- 
 0   2401                                                   74681 non-null  int64 
 1   Borderlands                                            74681 non-null  object
 2   Positive                                               74681 non-null  object
 3   im getting on borderlands and i will murder you all ,  73995 non-null  object
dtypes: int64(1), object(3)
memory usage: 2.3+ MB
None

Preview of Dataset:
   2401  Borderlands  Positive  \
0  2401  Borderlands  Positive   
1  2401  Borderlands  Positive   
2  2401  Borderlands  Positive   
3  2401  Borderlands  Positive   
4  2401  Borderlands  Positive   

  im getting on borderlands and i will murder you all ,  
0  I am coming to the borders and I will kill you...     
1  im getting on borderlands and i will kill you ...     
2  im coming on borderlands and i will murder you...     
3  im getting on borderlands 2 and i will murder ...     
4  im getting into borderlands and i can murder y...     

Categorical columns to encode: ['Borderlands', 'Positive']

Preprocessed Data Info:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 74681 entries, 0 to 74680
Data columns (total 3 columns):
 #   Column       Non-Null Count  Dtype
---  ------       --------------  -----
 0   2401         74681 non-null  int64
 1   Borderlands  74681 non-null  int32
 2   Positive     74681 non-null  int32
dtypes: int32(2), int64(1)
memory usage: 1.1 MB
None

Target column 'Positive' found and separated successfully.

Data split into training and testing sets successfully.
Training set size: (59744, 2)
Testing set size: (14937, 2)

Decision Tree Classifier trained successfully.

Decision tree visualization saved at: /mnt/data/decision_tree_visualization.png


Accuracy of Decision Tree Classifier: 0.37176139787105844

Classification Report:
               precision    recall  f1-score   support

           0       0.34      0.25      0.29      2661
           1       0.47      0.32      0.38      4471
           2       0.33      0.59      0.42      3551
           3       0.38      0.32      0.35      4254

    accuracy                           0.37     14937
   macro avg       0.38      0.37      0.36     14937
weighted avg       0.39      0.37      0.36     14937


