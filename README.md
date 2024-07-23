# Exploring bank data and determining loan grant

-Firstly, I sourced the bank data from kaggle using the pd.read_csv().
-Then, I did general inspection of the data using shape property, info method and describe method.
-Then, I analyzed the data by finding the correlation, plotting lmplot, plotting histplot and plotting scatter plot.
-Then, I chose Income, Education, Credit card average score and CD account as predictor variable and stored it in X.
-Then, I stored the target variable Personal.Loan in Y.
-Then, I splitted the X and Y into 80 % training and 20 % testing data.
-Then, I created a logistic regression model.
-Then I trained the model with training data.
-Then, I predicted the value for training data and testing data.
-Then I calculated the training accuracy and testing accuracy.
-Then I wrote a code, where users can enter their name, income, education, credit card average score and cd account. The information entered by user is fed to the model and users gets to know if or not the loan is granted.
