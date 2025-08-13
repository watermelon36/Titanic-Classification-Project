# Titanic-Classification-Project
Class: Summer Machine Learning Class 2025 (STEMPEERS) 
<br>
Instructor: Bhishan Poudel 
<br>
Programmer: Shriya Kanikaram 
<br>
Date: 8/13/2025
<br>
Note: In order to download the csv locally into google collab, run the very first cell and enter these values when prompted to. username":"shriyakanikaram","key":"d206e554e65c991b96ba80d35f7ed805
<br>
<br>
Project Details: I made a project to see what factors of a passnger could have lead to their survival or demise in the tragic event of the Titanic. I used Google collab to make my classification project and made a total of three models: logistic regression, decision tree, and random forest. At first I made many plots with all of the information of the passngers os I could see which variables had correlation with survival, so I would know which variables could be used to make the most accurate model.The features I used to rain the models were ticket class,age, amount of sibilngs/spouses, total ticket cost, count of prents/children, total count of family size, those who traveled alone, and ticket cost per person. For the features that were non-numerical, I encoded it so that each distinct value was made a new column and was converted into binary numbers so that it could be used to train the data as machine learning models can not directly train model with non-numeric values. Aditionally, I used scalar to make the standard deviation 1 and mean 0 so that each feature would almost equally contribute to the learning of the model. I used all three models so that I could check which model had the highest accuracy rate so I would know which I should use. The method that I found most accurate was logistic regression as it had a higher accuracy rate of prediction at 83%. The decision tree model had an accuracy of 73% and the random forest model had an accuracy of 80%. Some other metrics I used to evaulate my models precision, F!-score, recall, and support. I additionally used the confusion matrix metrics to evaulate my model as well. Finaly, after I found out that the logistic regression model had the highest accuracy out of the other two models, I fine tuned the parameters using Grid Search CV so that the accuracy increased to 85%. 

