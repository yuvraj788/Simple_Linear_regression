# Linear Regression Model  

Linear regression is a fundamental technique in machine learning used to model the relationship between a dependent variable and one or more independent variables.  

---

## Step 1: *Plot Actual vs Model Graph*  
- Visualize the actual data points.  
- Apply the model and compare the predictions to the actual data.  
- Identify the differences between the observed and predicted values.  

---

## Step 2: *Simple Linear Regression: How to Make a Model*  

### Key Concepts  
1. **Linear Equation**:  
   \[
   f_{wb} = wx + b
   \]  
   - **w**: weight or slope of the line.  
   - **b**: bias or y-intercept.  

2. **Initialization**:  
   Assign initial values to **w** and **b**, refined during training.  

3. **Model Output**:  
   Use the equation to predict the dependent variable (**f_{wb}**) for given inputs (**x**).  

---

## Step 3: *Making the Model*  
- Implement the linear regression formula to compute predictions for input data.  
- Calculate the predicted values (**f_{wb}**) for all observations.  

---

## Step 4: *Plotting Graphs*  
- Visualize the relationship between actual data and model predictions.  
- Compare the graphs to evaluate model performance.  

---

## Step 5: *Cost Function*  

### Definition  
- Measures the error between predicted values and actual values.  
- Indicates how well the model performs.  

### Purpose  
- Minimize the cost function to make predictions as close as possible to the actual data.  

### Formula  
\[
\text{Cost} = \frac{1}{2m} \sum_{i=1}^m (f_{wb}[i] - y[i])^2
\]  
Where:  
- **m**: Number of data points.  
- **f_{wb}[i]**: Predicted value for the **i-th** data point.  
- **y[i]**: Actual value for the **i-th** data point.  

---

## Step 6: *Gradient Descent Algorithm*  

### What is Gradient Descent?  
- An optimization algorithm to minimize the cost function.  
- Iteratively updates parameters (**w** and **b**) to reduce the error.  

### Purpose  
- Computes gradients of the cost function with respect to **w** and **b**.  
- Guides parameter adjustments to reach optimal values.  

---

## Step 7: *Applying Gradient Descent*  
- Update **w** and **b** using computed gradients.  
- Repeat the process over iterations until the cost function converges (error minimized).  

---

## Final Steps:  
1. Visualize the actual vs model graphs after optimization.  
2. Evaluate the model by observing prediction accuracy.  
3. Ensure **w** and **b** are optimized for the best fit.  

---

## Summary  
- **Step 1:** Plot actual vs model data for initial comparison.  
- **Step 2-3:** Define the linear equation and calculate predictions.  
- **Step 4:** Visualize the model's predictions against actual data.  
- **Step 5:** Use the cost function to measure error.  
- **Step 6-7:** Apply Gradient Descent to minimize error and refine the model.  
- **Final Step:** Evaluate the model and visualize results.  

---

### Key Takeaway:  
Linear regression simplifies the relationship between input and output, while the Gradient Descent Algorithm ensures the model becomes accurate by minimizing error.  
