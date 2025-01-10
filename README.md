# Simple_Linear_regression
# Linear Regression Model

Linear regression is a fundamental technique in machine learning used to model the relationship between a dependent variable and one or more independent variables.

---

## Step 1: *Plot Actual vs Model Graph*
- Start by visualizing the actual data points.
- Apply the model and compare the model predictions to the actual data.
- This step helps to identify the difference between the observed and predicted values.

---

## Step 2: *Simple Linear Regression: How to Make a Model*

### Key Concepts
1. *Linear Equation*: The model is represented as:
\[
   f_{wb} = wx + b
\]
   Where:
   - 👦w👦: weight or slope of the line.
   - 👦b👦: bias or y-intercept.

2. *Initialization*: Assign initial values to 👦w👦 and 👦b👦. These values will be refined during the training process.

3. *Model Output*: Use the equation to predict the dependent variable (👦f_{wb}👦) for given inputs (👦x👦).

---

## Step 3: *Making the Model*

- The goal is to implement the linear regression formula to compute predictions for the input data points.
- Iterate through the data to calculate the predicted values (👦f_{wb}👦) for all observations.

---

## Step 4: *Plotting Graphs*

- Visualize the relationship between the actual data and the model's predictions.
- Compare the two graphs to evaluate how well the model fits the data.

---

## Step 5: *Cost Function*

### Definition
- A cost function measures the error between the predicted values and the actual values.
- It helps to understand how well or poorly the model is performing.

### Purpose
- The primary goal of linear regression is to *minimize the cost function*.
- This ensures the model predictions are as close as possible to the actual data.
### Formula
The cost function for linear regression is defined as:
\[
\text{Cost} = \frac{1}{2m} \sum_{i=1}^m (f_{wb}[i] - y[i])^2
\]
Where:
- 👦m👦: Number of data points.
- 👦f_{wb}[i]👦: Predicted value for the 👦i^{th}👦 data point.
- 👦y[i]👦: Actual value for the 👦i^{th}👦 data point.

---

## Step 6: *Gradient Descent Algorithm*

### What is Gradient Descent?
- Gradient Descent is an optimization algorithm used to minimize the cost function.
- It updates the parameters (👦w👦 and 👦b👦) iteratively to reduce the error.

### Purpose
- The algorithm computes the gradients of the cost function with respect to 👦w👦 and 👦b👦.
- These gradients guide the adjustment of 👦w👦 and 👦b👦 to reach the optimal values.

---

## Step 7: *Applying Gradient Descent*

- Use the computed gradients to update the values of 👦w👦 and 👦b👦.
- Repeat the process over multiple iterations until the cost function converges (i.e., the error is minimized).

---
## Final Steps:
1. Visualize the actual vs model graphs after optimization.
2. Evaluate the model by observing how well it predicts the data.
3. Ensure the values of 👦w👦 and 👦b👦 are optimized for the best fit.

---

## Summary
- *Step 1:* Plot actual vs model data for initial comparison.
- *Step 2-3:* Understand and define the linear equation and predictions.
- *Step 4:* Visualize the model’s predictions against actual data.
- *Step 5:* Use the cost function to measure the error.
- *Step 6-7:* Apply Gradient Descent to minimize the cost and refine the model.
- *Final Step:* Evaluate the model's accuracy and visualize the results.

---

### Key Takeaway:
Linear regression simplifies the relationship between input a and output, and the Gradient Descent Algorithm ensures that the model becomes as accurate as possible by minimizing error.
