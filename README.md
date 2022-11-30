# ML-LinearRegression
In Statistics, Linear Regression is a linear approach for modelling the relationship between a scalar response and one or more explanatory variables.Linear Regression is used in this project to fetch us a linear relationship with the features of the car and the selling price in order to deliver us a mort accurate price in reference to the data on which the model is being trained.


## Here we have our data sheet
(source:CarDekho.com)
![](Car%20Price%20Prediction/images/Screenshot_20221130_080628.png)

### And our major focus is on the Selling Price 
![](Car%20Price%20Prediction/images/Screenshot%202022-11-30%20080750.jpg)

### So Lets Get On To The Project
In the [model.ipynp](Car%20Price%20Prediction/model.ipynb) file we have imported necessary libraries to perform various mathematical operations and training on and from the data and we have imported the csv file aswell.
![](Car%20Price%20Prediction/images/Screenshot%202022-11-30%20082718.jpg)

### Fetch the Company name and plot a heat map for the non-categorical values
We here fetched the first name of the company and then replaced it with the name of the car as this feature increased the accuracy of prediction of the model.
![](https://user-images.githubusercontent.com/104179274/204697913-d35ede18-80c0-4c89-b16e-f2d7d4acf591.png)

### Finding categorical variables and then inserting dummies
We here removed the outliers which could affect our model and thus we inserted dummies for all the categorical variables
![](Car%20Price%20Prediction/images/Screenshot_20221130_043009.png)
A dataset may contain various type of values, sometimes it consists of categorical values(fuel_type,owner etc.). So, in-order to use those categorical value for programming efficiently we create dummy variables. A dummy variable is a binary variable that indicates whether a separate categorical variable takes on a specific value.

![](Car%20Price%20Prediction/images/Screenshot_20221130_044053.png)

## Model
Subsequently test train split is called and the model is trained
![](Car%20Price%20Prediction/images/Screenshot_20221130_044353.png)
![](Car%20Price%20Prediction/images/Screenshot_20221130_044410.png)
Thus we have now obtained an accuracy of around 77% 

## One Hot Encoding and pickle file generation
![](Car%20Price%20Prediction/images/Screenshot_20221130_045043.png)
![](Car%20Price%20Prediction/images/Screenshot_20221130_045111.png)


## Website 
We did create a front end and linked with the pickle file leading us to the easier access to the model interface
![](Car%20Price%20Prediction/images/Screenshot_20221130_042744.png)
