
Computer Science Department
CS675 – Introduction to Data Science – Spring 2024
Professor Krystyn Gutu
Project #2 | Due: October 24, 2024
This is the continuation of Project #1. You have performed the very important step of Explanatory Data
Analysis (EDA) on Customer Churn data within the Telecommunication industry.
It is very common for companies to focus energy on combating customer churn, but the reality is that
once they’ve identified a customer who is about to leave, it’s often too late to entice them to stay.
The key is to identify customers at risk of churn early, before they get too far down the path, and to take
preemptive action to retain them and improve the customer relationship.
This is where Advanced Analytics (Machine Learning and Deep Learning modeling) comes into play.
Using Data Science and AI approaches to predict which of the customers will be loyal and which will
lapse. Your ML model(s) will help the company’s executives to understand what makes a great or bad
customer so they can take action.
Teaching machines to predict customer behavior, and communicate which customer attributes predict
specific behaviors, allows management to help build an organizational playbook for acquiring and
keeping happy customers. For example, a client success organization can reach out before there's a
problem, their marketing department can reach new customers that are less likely to churn, and their sales
organization can bring these better customers on board.
This problem is a typical classification task. You must build Machine Learning models to predict
whether a customer will churn or not.
You are asked to perform two (2) stages of analysis, based on different distribution of data:
1) Fit your models on the original (given) dataset
2) Fit your models on the modified dataset, after applying the SMOTE technique.
The Machine Learning models to be used are:
• Naïve Bayes
• Logistic Regression
• Random Forests
• XGBoost
The metrics of performance of the chosen models should be, with huge emphasis to recall:
• Accuracy
• Precision
• Recall
• F1-Score
Pace University CS675 – Introduction to Data Science Fall 2024
Professor Gutu Page 2 of 2
You should follow the standard ML workflow process while building your models:
• Explanatory Data Analysis (already done!)
• Data Visualization (already done!)
• Data Preprocessing (Data Imputation, Feature Selection & Scaling, Encode Categorical Features)
• Address Data Imbalance (apply the SMOTE technique)
• Split the training/test datasets in the 80/20 % ratio
• Algorithm Selection
• Modeling Building
• Modeling Evaluation
• Model Tuning (Hyperparameters Tuning)
Churn rate is a critical metric of customer satisfaction. Low churn rates mean happy customers; high
churn rates mean customers are leaving you. A small rate of monthly/quarterly churn compounds over
time. 1% monthly churn quickly translates to almost 12% yearly churn.
The dataset (telco-customer-churn.csv) is available for you to download and has 7043 rows and 21
columns. This is the same dataset used for the previous project.
NOTE: You do NOT need to build/select a model. You only need to perform a deep-dive analysis.
Write Python scripts in order to complete the following tasks along with their output. All work should be
done and submitted in a single Jupyter Notebook.
1) Prep the data in order to be ready to be fed to a model. Look for missing, null, NaN records.
Find outliers. Transform data – all entries should be numeric.
2) List all types of data, numeric, categorical, text.
3) Perform EDA. Present dependencies and correlations among the various features in the data.
List the most important variables (Feature Importance) that will affect the target label.
4) Split the dataset into training and test datasets (80/20 ratio). Using SweetViz’s ‘compare’
command contrast the training vs test datasets on the target (‘churn’)
5) State limitations/issues (if any) with the given dataset.
