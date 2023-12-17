# MastersThesisCS23
Details about my masters thesis at BTH Karlskrona, Sweden.


Rafique, Muhammad Ahmad Imran, and Lokesh Kola. "Exploring Machine Learning Techniques and Metric Feature Pairs for Software Defects Prediction." (2023).

*Tools Used* : Python, scikit-learn, pandas, numpy, tensorflow, excel, latex, Tableau etc
*Code of the study* : upload permission pending

## Abstract
### Background :- 
Software Defect Prediction is important in identifying potential is-
sues in software systems, improving software quality, and reducing development and
maintenance costs. Diverse methodologies, ranging from rule-based systems to ma-
chine learning, offer various approaches to defect prediction. However, the challenge
of class imbalance due to fewer instances of defective entities impacts model per-
formance. This thesis investigates machine learning techniques and feature-metric
pairs for defect prediction, including metric selection, using machine learning meth-
ods, and dataset creation using techniques like SMOTE to address class imbalance
and see how they impact predictive performance.

### Objectives :- 
The objective of this research is to i) explore feature-metric pairs
ii) see what aspects of the software impact prediction quality iii) see how different
machine learning algorithms behave and offer results iv) check the impact of class
imbalance and oversampling techniques v) analyze and check how models behave and
what can be done to improve them

### Methods :- 
We created two datasets using SMOTE and one without SMOTE,
applied various feature selection techniques, and scored them to find which were im-
portant, and used machine learning models to check how useful they are in predicting
software defects. The performance metrics recorded are time, accuracy, F1 Score,
precision, and recall. A scikit-learn pipeline was created in order to handle these
tasks from data addition to prediction.

### Results :- 
Our results indicate that most size and documentation metrics are impor-
tant features, despite their simplicity, in predicting defects. Despite the models not
being tuned enough, ensemble techniques worked really well in the process. SMOTE
trained datasets yielded better F1 Scores but most of their precision quality is not
acceptable. Voting classifier models performed the best amongst the feature-model
batch in terms of accuracy,F1 Score with the non-SMOTE version at 75%,57% and
the SMOTE one at 75%,58% respectively.

### Conclusions :- 
The conclusion shows that size and documentation metrics, despite
their simplicity, are noticeably important factors for defect prediction and that en-
semble techniques can be used and further tuned for the task as they offer the most
balanced performance in the experiment.

