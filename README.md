Regarding my 'Mine prediction' project, here i follow a general work flow to accomplish the goal of my project
The data file of the 'Mine prediction' project [Copy of sonar data.csv](https://github.com/user-attachments/files/16127093/Copy.of.sonar.data.csv)
Work flow : 1. Loading the data and then analysing it using head,shape, describe and value counts functions
            2. Creating out test and train data set, we first do this by seperating the label from the features, so that we can split the label into test and train aswell. As that is the basis on which we test our data on both train and test set
            3. We load our logistic regression training model under a variable and train it with our label and feature training set
            4. Evaluating our model using accuracy score with our training and test training data set 
            5. Getting user input and printing the outcome for one row, a set of features.
