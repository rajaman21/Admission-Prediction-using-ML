# Admission-Prediction-using-ML

Objective:
The project aims to predict the likelihood of a student's admission to various colleges based on their academic performance metrics and rankings.

Data Used:
The dataset comprises several key columns, including:

10th Marks: Scores obtained in 10th-grade exams.
12th Marks: Scores obtained in 12th-grade exams.
12th Division: Division ranking in 12th grade.
AIEEE Rank: Rank from the All India Engineering Entrance Examination.
College: The target label indicating which college the student may gain admission to.
Data Preprocessing:
Data preprocessing involves encoding categorical variables, such as college names, and separating the dataset into features (X) and target labels (y). Label encoding is applied to convert college names into numerical codes, making them compatible with machine learning models.

Exploratory Data Analysis (EDA):
Visualization techniques, including histograms and density plots, are utilized to analyze the distribution of student marks and rankings. Plots are created for features such as 10th marks, 12th marks, 12th division, and AIEEE rank.

Machine Learning Models Used:
The project employs the following models:

XGBoost Classifier: A gradient boosting classifier optimized for multi-class classification to predict admission probabilities for multiple colleges.
Decision Tree Classifier: A simpler model used as a comparative alternative to XGBoost to evaluate accuracy and efficiency.
Model Evaluation:
The models are assessed based on their accuracy scores on test data. The Decision Tree Classifier demonstrated a higher accuracy of 96% compared to the XGBoost Classifier, which achieved 75%.

Prediction Functionality:
The project features a functionality that allows users to input their academic details to predict college admissions. For instance, by entering values such as 10th and 12th marks, division, and AIEEE rank, the model can forecast the likely college for admission.

Results Visualization:
A confusion matrix is utilized to visualize the comparison between predicted and actual outcomes, providing insights into model performance across different colleges.

Libraries and Tools:
The project employs several Python libraries, including:

pandas and numpy for data manipulation.
matplotlib and seaborn for data visualization.
scikit-learn for building and evaluating models.
XGBoost for implementing the XGBoost Classifier.
Conclusion:
This project showcases a machine learning approach to predicting college admissions based on academic records. It emphasizes the comparison between different models and illustrates how these predictions can assist prospective students in their decision-making process.
