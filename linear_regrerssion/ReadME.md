This code is to the blog that return over here : https://medium.com/@purnasaigudikandula/linear-regression-in-python-with-cost-function-and-gradient-descent-bde9a8d2626

 A littile gimpse of blog here

**Machine learning has Several algorithms like:**

1.Linear regression

2.Logistic regression

3.k-Nearest neighbors

4.k- Means clustering

5.Support Vector Machines

6.Decision trees

7.Random Forest

8.Gaussian Naive Bayes

Today we will look in to Linear regression algorithm.

# Linear Regression:

Linear regression is most simple and every beginner Data scientist or Machine learning Engineer start with this. Linear regression comes under supervised model where data is labelled. In linear regression we will find relationship between one or more features(independent variables) like x1,x2,x3………xn. and one continuous target variable(dependent variable) like y.

**The thing is to find the relationship/best fit line between 2 variables.**
if it is just between the 2 variables then it is callled Simple LinearRegression. if it is between more than 1 variable and 1 target variable it is called Multiple linearregression.

# Equation:
1. for simple linear regression it is just

y = mx+c , with different notation it is

y =wx +b.

where y = predicted,dependent,target variable. x = input,independent,actual

m(or)w = slope, c(or)b = bias/intercept.


![alt text](https://github.com/purnasai/Linear_regression_with_blog/blob/master/linear_regrerssion/Linear_Regression.png)

and gradient Descent looks like 
![alt text](https://github.com/purnasai/Linear_regression_with_blog/blob/master/linear_regrerssion/Gradient_descent.png)

for more and clear explanation check out this excellent blog [here](https://medium.com/@purnasaigudikandula/linear-regression-in-python-with-cost-function-and-gradient-descent-bde9a8d2626)




# Overview:
Linear_regression.ipynb--> is the code file that you should run in CMD.
ReadME.md--> is the window that you are reading now with information.
bmi_and_life.csv--> is the dataset of BMI vs LIFE EXPECTANCY
requriements.txt--> has libraries with version that you should install if not.



# Dependencies:

pandas
scikit-learn
matplotlib
You can just run '''pip install -r requirements.txt''' in terminal to install the necessary dependencies.

# Usage:

Type python linear_regression.py into terminal and you'll see the scatter plot and line of best fit appear.



