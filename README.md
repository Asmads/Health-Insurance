# Health-Insurance
Health Insurance EDA and ML Algorithms

INTRODUCTION TO DATA SCIENCE


PROJECT REPORT


HEALTH INSURANCE CROSS SELL PREDICTION DATASET











DATASET LINK:
https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction

ABSTRACT:
Using the dataset provided, we built a simple model using the health insurance dataset to predict, whether the customer would be interested in Vehicle insurance or not. Basically we want to predict that will the customers from past year also be interested in Vehicle Insurance provided by the company.
DATASET ATTRIBUTES:
Our dataset contains 12 features, 381109 data records in training dataset, 127037 records and 11 features in our testing dataset excluding the ‘response’ feature. We have merge testing and training dataset then the total features are 12 and records after merging are 508146. Testing csv file contain all features except ‘response’ because ‘response’ is the target variable.
ATTRIBUTES NAMES:
ID
Gender
Age
Driving_License
Region_Code
Previously_Insured
Vehicle_Age
Vehicle_damage
Annual_Premium
Policy_Sales_Channel
Vintage
Response
TARGET VARIABLE:
Response is our target variable which we have to predict.
METHODS:
EXPLORATORY DATA ANALYSIS:
We have applied 70% EDA as per our teacher requirements.
We have used libraries like pandas, numpy, seaborn, matplotlib.
By using pandas we import our datasets and use some pandas functions to do statistical analysis, and then using seaborn and matplotlib library we have done visualization of our data set,and found relationships between features.
We have found interested and not interested customers in vehicle insurance according to Region_Code and Policy_Sales_Channel then we have converted the ages of the customers into classes and then we have found the interested and not interested customers count according to ‘Age’ class.
Using seaborn package we have made some bar graphs for the better understanding of features.









Here in the above figure, we have made a bargraph of Vehicle_damage and Age to see the mean age of the customers who got his/her vehicle damaged in the past is higher and around mid 40s as compared to who didn't had their vehicles damaged with mean age around early 30s.









In this figure we have checked the response count of Interested and Not_Interested customers.









Then here in above figure we have checked the Count of Gender and we have found out that Male customers are more interested in vehicle insurance as compared to female Customers.










Here we have made a bargraph of Gender and Customers who were previously Insured or Not Insured. So here we have found out that there are more male customers who Insured previously than females.
And at last we have calculate the count of customers according to some features like Policy_sales_channel, Ages and region_Code.
MACHINE LEARNING:
We have applied 30% Machine Learning Algorithms as per our teacher requirements.
We have applied 2 Algorithms on this dataset.
Logistic Regression
Decision Tree Classifier
We have applied these algorithms and found out the accuracy that which algorithm performs better on this dataset.
Firstly we have applied Label Encoding to make our dataset into numerical form by using Label Encoder Library then we have applied the Algorithms to check the accuracy.
Logistic Regression:
We have imported a library and applied this Algorithm on both  
test and train dataset and then check which features are important   then we found out that the accuracy of this algorithm on train csv is  0.8766, and the accuracy of this algorithm on test csv is 0.9992.

Decision Tree Classifier:
We have imported a library and applied this Algorithm on both  
test and train dataset and then check which features are important   then we found out that the accuracy of this algorithm on train csv is  0.9832, and the accuracy of this algorithm on test csv is 0.8812.

Conclusion:
In this report we have predict the outcomes of our dataset by 
applying some statistical and Machine Learning models.
EDA:
The customers who are not previously insured are more interested with the figure of 46,552 than the customers who are previously insured with the figure 158 so we can assume that the customers who are previously insured and are not taking interest is because there pervious insurance is not expired yet.
 
Customers who have a driving license are more interested with the figure of 46,669 than the customers who does not have a driving license with the figure 41,so we can assume that they have not got the liscense yet therefore they are not interested in the insurance. 
 
Customers who’s vehicle age is between 1 to 2 years are most interested with the figure of 34,806 followed by the figure of 7,202 ,the customers who are interested and there vehicle age is less than 1 year and at last the least figure is of 4,702 these are the customers who’s vehicle age is more than 2 years.
Customers who have damaged vehicle are more interested with the figure of 45,728 than the customers who does not have a damaged vehicle with the figure 982.
The customers from the policy sales channel 26 are the most interested one with the figure of 15,891 than followed by the customers from the channel 124 which has 13,996 customers interested and so on.
The customers from the policy sales channel 83,105,62,88,46,51,27,14673,39132,etc are the least interested one with the figure of 0 than followed by the customers from the channel 48,69,49,97,etc which has 1 customer interested and so on.
The customers from the Region code 28 are the most interested one with the figure of 19,917.
The maximum number of days are 299 and the 169 out of 1,709 Customers are interested.
only 1 customer is interested and  is paying the maximum annual premium out of 4.
The most interested customers are from age group 42-52 with the figure of 16,569 followed by the age group 31-41 with the figure of 13,212 .
The customers from the age group 75-85 are the least interested one with the figure of 503.
ML:
In Logistic regression the accuracy on train csv is  0.8766, and the accuracy of this algorithm on test csv is 0.9992.
In Decision tree Classification the accuracy on train csv is  0.9832, and the accuracy of this algorithm on test csv is 0.8812.
So we can see that the accuracy of Decision Tree Algorithm is better than Logistic regression, So we can use this Model to Predict the insights from our dataset.

