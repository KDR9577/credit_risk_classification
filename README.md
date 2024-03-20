# credit_risk_classification
Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
Split the data into training and testing datasets by using train_test_split.
Fit a logistic regression model by using the training data (X_train and y_train).
Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluate the model’s performance by doing the following:
Generate a confusion matrix.
Generate a classification report.
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?


Credit risk analysis report

An overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to identify how well we can predict whether borrowers have either healthy credit profiles, or high-risk credit profiles.
The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
        accuracy score - the accuracy score of 99% is so high due to the fact that the model is able to correctly predict results of the larger subset of the data (healthy loans)
        precision score - the model was able to more accurately classify healthy loans as healthy than it was at classifying high-risk loans as high-risk        
        recall score - again, the model was able to more accurately classify healthy loans as healthy than it was at classifying high-risk loans as high-risk
A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
    The model is much better at predicting healthy loans than it is at predicting high-risk loans. I would recommend the model for assisting in making decsions regarding credit profiles. I wouldn't recommend that it be the only tool used in the evaluation given that it's less than 90% accurate at correctly predicting high-risk loans. Buying a home is the largest purhcase that most people will make in their liftime, so it's important that these decisions are correct. The lower precision and recall scores also help to support that recommendation.
