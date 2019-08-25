# A study on Facebook Customer Bahavior Prediction using Logistic Regression.
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
You have been hired as a consultant to a start-up that is running a targetted marketing ads on facebook. The company wants to anaylze customer behaviour by predicting which customer clicks on the advertisement. 
Customer data is as follows:

`Inputs:`
```
Name
e-mail
Country
Time on Facebook
Estimated Salary (derived from other parameters)
```

`Outputs:`
```
Click (1: customer clicked on Ad, 0: Customer did not click on the Ad)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting

### Instruction
1. Downloaded the [dataset](https://github.com/zhenyu92/ML_Logistic_Regression_FB_Customer_Prediction/blob/master/Facebook_Ads_2.csv).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_Logistic_Regression_FB_Customer_Prediction/blob/master/Logistic%20Regression%20-%20Customer_Prediction.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Exploring the Descriptive Statistics of the Variables
      3.2  Exploring the Variables
      3.3 Data Cleaning
      3.4 Data scaling
    4 Train Test Split
    5 Select and Train a Model
      5.1 Linear regression model
    6 Apply Model on Test Set
    7 Visualizing Training and Testing Datasets
    ```
    
### Model Performance
The model has an average `Precision` & `Recall` of 86%.
![alt text](https://github.com/zhenyu92/ML_Logistic_Regression_FB_Customer_Prediction/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
