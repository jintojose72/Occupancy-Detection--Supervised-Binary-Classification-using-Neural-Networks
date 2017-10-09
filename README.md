# Occupancy-Detection--Supervised-Binary-Classification-using-Neural-Networks

The goal of this project would be to correctly predict the occupancy of a room for certain parameters pertaining to that room. This is important since based on these parameters, the company/firm can decide what parameters to use for an ideal work environment to be present in a room.  
The dataset being used for this study is the “Occupancy Detection Data Set” from the reputed UCI Machine Learning Repository. Following are the parameters taken into consideration in the data set: -
1.	Temperature
2.	Humidity
3.	Light
4.	CO2
5.	Humidity Ratio
There are a total of 3 datasets provided by the repository – One for training and the other two are for testing. The training dataset consists of the above 5 parameters as well as a 6th field which is Occupancy which is denoted as 0 or 1 based on whether the room is not occupied or occupied. The following algorithms were trained with the training dataset and this data was used to test the test dataset: -
1.	Logistic Regression
2.	Linear Discriminant Analysis
3.	Naïve Bayes Classifier
4.	Quadratic Discriminant Analysis
The accuracy of each of these algorithms was found out on the test datasets and compared to each other to find out which was the best approach to find out the occupancy.

