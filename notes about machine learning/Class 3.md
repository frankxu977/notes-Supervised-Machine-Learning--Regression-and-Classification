
## Cost function formula

The content focuses on the foundational concepts of linear regression, particularly the cost function used to evaluate model performance.

Cost Function Definition

- The cost function measures ==how well the linear regression model fits the training data by comparing predicted values to actual targets.==
- It calculates the error as ==the difference between predicted values (y hat) and actual targets (y)==, and then ==squares this error.==
![[Pasted image 20251020101915.png]]
Parameters of the Model

- The model is defined by a linear function f_w, b of x = w * x + b, where ==w (weight) and b (bias)== are parameters that can be adjusted during training.
- Different values of w and b result in different lines on a graph, affecting the model's predictions.

Finding Optimal Parameters

- The goal is to choose values ==for w and b that minimize the cost function,== which is typically expressed as the average squared error across all training examples.
- The cost function is denoted as ==J(w, b) and is crucial for determining how well the model performs in predicting outcomes.==



## Cost function intuition

The content focuses on understanding the cost function in linear regression and its role in finding the best parameters for a model.

Cost Function Overview
- The cost function ( J ) measures the difference between the model's predictions and the actual values.
- The goal is to minimize ( J ) by adjusting the model parameters ( w ) and ( b ).
- ![[Pasted image 20251020102201.png]]

Simplified Linear Regression Model

- A simplified model is introduced where ( b ) is set to 0, making the function ( f_w(x) = w \cdot x ).
- The cost function ( J ) is now a function of only ( w ), and the objective is to find the value of ( w ) that minimizes ( J ).
![[Pasted image 20251020103359.png]]
Visualizing Cost Function and Model

- Graphs are used to illustrate how different values of ( w ) affect the model and the corresponding cost function.
- The relationship between the model's fit and the cost function is explored, showing that ==a lower cost indicates a better fit to the training data.==

