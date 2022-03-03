# Automobile-Price-Prediction

# ABSTRACT 
There are various factors that determine the price of a car. This makes the price 
prediction of cars a challenging task. To build a model for predicting the price 
of cars, we have applied three machine learning techniques (Linear Regression, 
Decision Trees and Random Forest). We employ these machine learning models 
that can accurately predict the price of a car based on its features, in order to 
make informed purchases. We implement and evaluate various learning 
methods on the dataset. Our results show that the Decision Tree and Random 
Forest Regressors yield the best results. Conventional linear regression also 
yielded satisfactory results, although its accuracy was not as high as the 
aforementioned algorithms. 

# PROBLEM STATEMENT 
The prices of new cars in the industry are fixed by the manufacturer with some 
additional costs incurred by the Government in the form of taxes. There is a need 
for a car price prediction system to effectively determine the worthiness of the 
car using a variety of features. Even though there are websites that offers this 
service, their prediction method may not be the best. Besides, different models 
and systems may contribute on predicting power for a car’s actual market value. 
Thus, building a system that accurately determines the price of cars is essential, 
relevant and necessary.

# OBJECTIVE
➢ The main aim of the project is to give an accurate prediction of the price of a car based on the features describing it. 
➢ To choose 3 machine learning models for training the dataset, to predict the prices with satisfactory accuracy.
➢ Pre-processing and cleaning of data is a prerequisite.
➢ Exploratory Data Analysis is necessary.
➢ To compare the accuracy of the three models used for prediction.
➢ To determine the most efficient algorithm among the three chosen model. 

# Exploratory Data Analysis:

1. Price vs Body Style
➢ The distributions of price between the different body-style categories have a significant overlap, and so body-style would not be a good predictor of price. 

2. Price vs Engine Size 
➢ The scatterplot between the "engine-size" and "price" indicates a positive linear relationship between the two.
➢ As the engine-size goes up, the price goes up: this indicates a positive direct correlation between these two variables. Engine size seems like a pretty good predictor of price since the regression line is almost a perfect diagonal line. The correlation between the two is found to be 0.872335. 

3. Price versus Highway-mpg
As the highway-mpg goes up, the price goes down: this indicates an inverse/negative relationship between these two variables. Highway mpg could potentially be a predictor of price. The correlation between the two is found to be -0.704692. 

4. Price vs Engine-Location 
The distribution of price between these two engine-location categories, front and rear, are distinct enough to take engine-location as a potential good predictor of price. 

5. Price vs Drive- wheels
Here we see that the distribution of price between the different drive-wheels categories differs; as such drive-wheels could potentially be a predictor of price.

6. Price vs Peak-rpm
Peak rpm does not seem like a good predictor of the price at all since the regression line is close to horizontal. Also, the data points are very scattered and 
far from the fitted line, showing lots of variability. Therefore it's it is not a reliable variable. The correlation between the two is found to be -0.101616.

7. Price vs Horsepower 
➢ As the highway-mpg goes up, the price goes down: this indicates an inverse/negative relationship between these two variables. Highway mpg could potentially be a predictor of price.
➢ We can examine the correlation between 'highway-mpg' and 'price' and see it's approximately -0.704.

# MACHINE LEARNING MODELS
➢ The type of task identified here is regression.
➢ The following three algorithms are implemented in this project for the given dataset:
✓ Linear Regression
✓ Random Forest (Regressors)
✓ Decision Trees (Regressors)

Linear Regression:
It predicts the outcome of a dependent variable based on the independent variables. The relationship between the variables is linear and hence the word 
linear regression.

R2 Score: 0.8092320637168342 

Random Forest Regressor:
A Random Forest is an ensemble technique capable of performing both regression and classification tasks with the use of multiple decision trees and a technique called Bootstrap and Aggregation, commonly known as bagging. The basic idea behind this is to combine multiple decision trees in determining the final output rather than relying on individual decision trees. 

R2 Score: 0.9377182890696486

Decision Tree Regressor:
Decision tree regression observes features of an object and trains a model in the structure of a tree to predict data in the future to produce meaningful continuous 
output. Continuous output means that the output/result is not discrete, i.e., it is not represented just by a discrete, known set of numbers or values.

R2 Score: 0.9012478421695049
 
 
<img width="510" alt="image" src="https://user-images.githubusercontent.com/45491462/156474691-d78f59d1-5f13-4028-85aa-ef6d6e72f9e8.png">

# Conlcusion
Upon exploring the dataset in detail, we found correlations between the attributes and the output. After data cleaning and pre-processing steps, we fed 
the dataset to three machine learning models that we found to be the most efficient and appropriate for the given task. On observing the results of the 
predictions, we found all the three algorthims to produce satisfactory results, with two being far more superior to the third, viz, Random Forest and Decision 
Trees showed much better performace results than the traditional Linear Regession algorithm.

