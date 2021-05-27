# customer-loan-risk-prediction
An organization wants to predict who possible defaulters are for the consumer loans product. They have data about historic customer behavior based on what they have observed. Hence when they acquire new customers, they want to predict who is risky and who is not.

Many a times, customers are unable to repay their loans, and hence marked as defaulters. The historical data of such customers can help predicting who in the future could be a risky customer. 

This hence becomes a Binary Classifier where we classify customers to risky and not risky. The data is split into training and test sets, and then the training data is processed, analysed and new cfeatures are extracted from the analysis. 

Then the important features are selected and fed into the model, which is a Random Forest Classifier algorithm. Then, we obtain the predictions for our test set and check our accuracy.

