This is my first submission in kaggle machine learning competition.It took me more than a month to really able to say that the notebook is quite simple.These are the 
end_to_end overview of whole program:
1.Feature Construction:converted 'SibSp' and 'Parch' to 'Family'.
2.Feature Splitting:Considered the salutation part of each name and custom encoded them based on survival rate.
3.I have simply eliminated PassengerId(not of any practical use),Cabin(70 percent missing values),Ticket(not able to utilize it).
4.Used SimpleImputer(strategy=most_frequent) to impute missing values in embarked.
5.One hot encoded name,sex and embarked colms.
6.Filled missing values in age column with iterative imputer.
7.applied power transformer to the whole dataset.
8.Used KNN algorithm with the optimal value of n_neighbors came out to ba 10.


#Got an accuracy_score of 83.73% on training dataset.
#Got score of 0.76076 in Kaggle

I uderstand it requires a lot of improvement.Wiil definitely try to enhance the model.
