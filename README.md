# Home Credit Default Risk (Kaggle)

Complete pipeline to preprocess the data, train the model and then predict values for the Home Credit Default Risk Kaggle competition.

This particular competition is a binary Classification task: we want to predict whether the person applying for a home credit will be able to repay its debt or not.

The dataset is composed of multiple files with different information about loands taken. In this project we're going to exclusively work with the main files: application_train.csv and application_test.csv.

The competition uses Area Under the ROC Curve as the evaluation metric, so our models will have to return the probabilities that a loan is not paid for each row.
