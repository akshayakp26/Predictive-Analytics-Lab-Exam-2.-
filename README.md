# Predictive-Analytics-Lab-Exam-2.-
Objective: The objective of this lab exam is to perform a classification task using machine learning techniques. The workflow includes Exploratory Data Analysis (EDA), data preprocessing, model building, decision boundary visualization, and performance evaluation.
the dataset used consits of feature1, Feature2, Target(Yes or No)

Exploratory Data Analysis (EDA):
The following steps were performed:
Checked for missing values using df.isnull().sum()
Handled missing values using:
Mean/Median for numerical features
Mode for categorical features

Visualizations used:
Countplot (class distribution)
Scatter plot (feature relationships)
Boxplot (outlier detection)
Heatmap (correlation analysis)
Pairplot (feature interaction)

Model Building
Model used: Logistic Regression
Initially, the model showed poor performance due to class imbalance
Improved model using class balancing techniques

Decision Boundary
Decision boundary was plotted using two selected features
Visualization shows how the model separates different classes

Model Evaluation
Initial Model Performance

Accuracy: 76.5%
Failed to classify minority class (Class 1)
Precision, Recall, F1-score for Class 1 were 0.00
Indicated class imbalance problem

Improved Model Performance

Accuracy: 93.5%
Confusion Matrix:
[[147   6]
 [  7  40]]

Classification Report:
Class 0:
Precision: 0.95
Recall: 0.96
F1-score: 0.96
Class 1:
Precision: 0.87
Recall: 0.85
F1-score: 0.86

Results

The improved model achieved high accuracy and balanced performance
Successfully handled class imbalance
Demonstrated strong predictive capability for both classes

Conclusion

The classification model was successfully developed and evaluated. Initially, the model suffered from class imbalance, but after applying improvements, it achieved high accuracy and balanced performance across both classes. Logistic Regression proved to be effective for this classification task.
