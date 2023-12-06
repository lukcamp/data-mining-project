In this project, I used Jupyter notebook tool, with Pandas dataframe to read the SQL commands from the python code, numpy and sklearn tools.


In this project, I filtered the database data using an SQL query, split the filtered data between train and test, and used an SGD classifier to train and compare with the untrained 
test data to determine how accurate the results were. In this particular case, I was looking to predict soccer match results and using this classifier I was able to get up to 47% 
accuracy using a 10 fold cross validation. There were other classifiers I experimented with (Random Forest, LinearSVC, SVM, Decision Trees), but the SGD seemed to be the more accurate
one.
