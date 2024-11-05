# rock_vs_mine
ML model that helps sonar prediction of rock and mine
This was my first Machine learning project, I used Logictic Regression method inorder to classify the data into rock or mine.
Steps followed throughout the process:

-> Data collection on Kaggle
->Analysis of data, what are the input parameters given, finding the mean based on the output, figuring out whether standardization is required and also determine approach to be taken to solve the problem.
-> Upload data on google colab
->import libraries- pandas, numpy, sklearn preprocessing model
->import data as a pandas dataframe
->Do preprocessing on the data - check rows, columns, mean, median, outcomes
->Split the columns into data and outcome
->Split the two dataframes into train and test model - here i used 80% train and 20% test.
->Apply logistic regression on the train model to help the model calculate the halfspace for classification.
->Check accuracy for train part first.
-> if above 70% proceed.
->if not, the model isn't fit for the problem statement.
->Check accracy for test model.
->Accuracy must be similar to train model, else it means that the logistic regression is biased towards the train set.
-> Finally deloy the model by creating any UI and testing it againts various other testcases.
