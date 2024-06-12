# Classifier Performance Evaluation
This project focuses on training and evaluating multiple machine learning models for a classification 
task related to loan approval prediction. The objective is to predict whether a loan will be approved 
based on a set of input features. The project utilizes popular classifiers from the scikit-learn library
 and assesses their performance using various metrics.


The following classification reports summarize the performance of each model used in predicting 
loan approvals. Each report includes precision, recall, F1-score, and support for each class.

## RandomForestClassifier:
Class 0 (Loan Not Approved): Precision: 0.64, Recall: 0.47, F1-Score: 0.54, Support: 34

Class 1 (Loan Approved): Precision: 0.81, Recall: 0.90, F1-Score: 0.85, Support: 86

Overall Accuracy: 0.78

Macro Avg: Precision: 0.73, Recall: 0.68, F1-Score: 0.70

Weighted Avg: Precision: 0.76, Recall: 0.78, F1-Score: 0.76

## GaussianNB:
Class 0 (Loan Not Approved): Precision: 0.79, Recall: 0.44, F1-Score: 0.57, Support: 34

Class 1 (Loan Approved): Precision: 0.81, Recall: 0.95, F1-Score: 0.88, Support: 86

Overall Accuracy: 0.81

Macro Avg: Precision: 0.80, Recall: 0.70, F1-Score: 0.72

Weighted Avg: Precision: 0.81, Recall: 0.81, F1-Score: 0.79

## DecisionTreeClassifier:
Class 0 (Loan Not Approved): Precision: 0.42, Recall: 0.50, F1-Score: 0.46, Support: 34

Class 1 (Loan Approved): Precision: 0.79, Recall: 0.73, F1-Score: 0.76, Support: 86

Overall Accuracy: 0.67

Macro Avg: Precision: 0.61, Recall: 0.62, F1-Score: 0.61

Weighted Avg: Precision: 0.68, Recall: 0.67, F1-Score: 0.67

## KNeighborsClassifier:
Class 0 (Loan Not Approved): Precision: 0.83, Recall: 0.44, F1-Score: 0.58, Support: 34

Class 1 (Loan Approved): Precision: 0.81, Recall: 0.97, F1-Score: 0.88, Support: 86

Overall Accuracy: 0.82

Macro Avg: Precision: 0.82, Recall: 0.70, F1-Score: 0.73

Weighted Avg: Precision: 0.82, Recall: 0.82, F1-Score: 0.80

# Conclusion

* Accuracy:
KNeighborsClassifier: 0.82
GaussianNB: 0.81

* Weighted Average F1-Score:
KNeighborsClassifier: 0.80
GaussianNB: 0.79

* Recall for Class 1 (Loan Approved):
GaussianNB: 0.95
KNeighborsClassifier: 0.97

### Best Performer:
The KNeighborsClassifier demonstrates the best overall performance:
Highest accuracy (0.82)
Highest weighted average F1-score (0.80)
Maintains a good balance of precision and recall across both classes
Overall, the KNeighborsClassifier is recommended due to its superior performance in accuracy, F1-score, and recall for loan approval prediction.

### Technologies
Programming Language: Python
Libraries: Pandas, Scikit-learn, Matplotlib, Numpy
