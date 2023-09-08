# Implementing-Logistic-Regression
## Task
Implement the Logistic Regression from scratch.
## Description
- Best suited for Binary Classification Problem
- Uses Sigmoid Function</br>
Y' = 1/(1+e^-z)</br> 
z = w.X + b</br>
Y': Probability of Y=1 with respect to given X</br>
X: feature</br>
w: Wieght</br>
b: Bias</br>
- Gradient Descent for Logistic Regression</br>
w = w - L.Dw</br>
b = b - L.Db</br>
w: Weight</br>
b: Bias</br>
L: Learning Rate</br>
Dw: Change in weight = 1/m * (Y' - Y).X</br>
Db = Chenge in bias = 1/m * (Y' - Y)</br>
## Steps to build a optimise model using Logistic Regression
- step 1: Set Learning Rate and Number of Iteration, Intiate Random Weight and Bias value
- Step 2: Build Logistic Regression FUnction. (Sigmoid Function)
- Step 3: Update the parameter using Gradient Descent
- Step 4: Build the "Predict function" to determine the class of the data point.
## Implement the Built model
- Import necessary libraries
- Load the diabetics dataset and split into feature and target
- Perform Data Standardization 
- Load the model
- Split the dataset into training and test data
- Predict the model for both training and test data:
  - Accuracy score for trained data:  0.7768729641693811
  - Accuracy score for test data:  0.7662337662337663 </br></br></br>

  Reference: 7.2.5. Building Logistic Regression from scratch in Python, Siddhardhan, https://www.youtube.com/watch?v=HDr6ONzE9uM&list=PLfFghEzKVmjsNtIRwErklMAN8nJmebB0I&index=91
