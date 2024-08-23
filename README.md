# Credit_Risk_Classification

An overview of the analysis: Explain the purpose of this analysis.
The goal was to predict the status of a loan ( if it was healthy or unhealthy) based on the data used to train the model.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

Negative Class (0):
    -Precision: 1.00
The model is perfectly accurate when predicting the negative class. Every time it predicts a negative loan, it is correct.
    -Recall: 1.00
The model correctly identifies all actual negative loans. There are no false negatives in this class.
    -F1-score: 1.00
The F1-score is perfect, reflecting both perfect precision and recall for the negative class. 

Positive Class (1):
    -Precision: 0.87
When the model predicts a loan is positive (high-risk), it is correct 87% of the time. This indicates some false positives are present.
    -Recall: 0.91
The model correctly identifies 91% of the actual positive loans, meaning it misses 9% of them (false negatives).
    -F1-score: 0.89
The F1-score reflects a balance between precision and recall, showing the overall effectiveness in predicting positive loans.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

The model is extremely accurate in predicting the correct Nagative Class with a 100% F1 Score. However, when predicting the Positive Class the model has an F1 Score of 89%. This may be due to the low amount of training data for that category, although 89% is still very high. Overall, the high accuracy and strong average metrics indicate that the model is highly effective in distinguishing between the two classes (99%), with a very low rate of misclassification.