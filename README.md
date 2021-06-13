# Linear-Regression
A Python project to demonstrate linear regression on data using single variable and multiple variables.

# Tools & Applications
- Pycharm Community Edition 2020.3.3
- Python 3.7/3.8

# Description
- ## Linear regression with one variable
In this part of this exercise, you will implement linear regression with one variable to predict proﬁts for a bakery franchise. 
Suppose you are the Chief Executive Officer of a bakery and are considering diﬀerent cities for opening a new outlet. The chain already has outlets in various cities and you have data for proﬁts and populations from the cities. You would like to use this data to help you select which city to expand to next.

The ﬁle ex1data1.txt contains the dataset for our linear regression problem. The ﬁrst column is the population of a city and the second column is the proﬁt of an outlet in that city. A negative value for proﬁt indicates a loss.

-  ## Plotting the Data
Before starting on any task, it is often useful to understand the data by visualizing it. For this dataset, you can use a scatter plot to visualize the data, since it has only two properties to plot (proﬁt and population). (Many other problems that you will encounter in real life are multi-dimensional and can’t be plotted on a 2-d plot.)
The plot should look like Figure 1, with the same red “x” markers and axis labels.

![image](https://user-images.githubusercontent.com/85407775/121798300-e52e7d80-cc3e-11eb-9159-89f8c52f5008.png)

- ## Gradient Descent
In this part, you will ﬁt the linear regression parameters θ to our dataset using gradient descent.

- ## Update Equations
The objective of linear regression is to minimize the cost function
![image](https://user-images.githubusercontent.com/85407775/121798330-1ad36680-cc3f-11eb-9af7-a2356c2f5cc1.png)
![image](https://user-images.githubusercontent.com/85407775/121798338-23c43800-cc3f-11eb-9a9e-684f97415a37.png)
![image](https://user-images.githubusercontent.com/85407775/121798345-29ba1900-cc3f-11eb-8584-5737b5fc3541.png)

