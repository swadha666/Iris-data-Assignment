Which metric is more important if misclassification is costly? (Task 1)
Recall or Precision  depending on the cost.
If missing a positive case is expensive (medical diagnosis, fraud detection) → Recall
If false alarms are expensive (spam filters, legal cases) → Precision

Which error occurs more: False Positives or False Negatives? (Task 2)
False Positives usually occur more here. 
Why?
Setosa is linearly separable → almost zero FN
Logistic Regression slightly over-predicts Non-Setosa

Which model generalizes better and why? (Task 3)
Logistic Regression. Period.
Why?
Smaller gap between training and testing accuracy
Less sensitive to noise
Decision Tree memorizes the training data → overfits
