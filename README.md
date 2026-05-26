# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br> Import the required libraries numpy and LinearRegression.

### Step2
<br> Create the input data X and output data y using NumPy arrays.

### Step3
<br> Create the Linear Regression model and train it using the fit() method.

### Step4
<br> Display the coefficient and intercept values of the trained model.

### Step5
<br> Predict the output for the new input [[3,5]] using the predict() method and display the result.

## Program:
```

import numpy as np
from sklearn.linear_model import LinearRegression

X = np.array([[1, 1], [1, 2], [2, 2], [2, 3]])
y = np.dot(X, np.array([1, 2])) + 3

reg = LinearRegression().fit(X, y)

reg.score(X, y)

print('Coefficients: ', reg.coef_)
print('Intercept: ', reg.intercept_)

print('Prediction: ', reg.predict(np.array([[3, 5]])))

```
## Output:

### Insert your output

<br> <img width="616" height="471" alt="image" src="https://github.com/user-attachments/assets/74cca7b1-28ea-4e85-8221-8943a2a2648a" />


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
