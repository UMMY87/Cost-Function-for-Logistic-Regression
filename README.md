# Cost Function for Logistic Regression
The provided code generates various visualizations and computations related to logistic regression. Here's a breakdown of each part:

1. **Plotting Data Points:**
     The first plot visualizes the dataset consisting of six data points with two features each. The points are plotted on a 2D plane, with the x-axis representing the first feature ($x_0$) and the y-axis representing the second feature ($x_1$).

![plot-data-points](https://github.com/UMMY87/Cost-Function-for-Logistic-Regression/assets/117314436/7b6cca34-bf21-4cd8-af51-7014caa3fb42)

2. **Computing Logistic Cost:**
     The `compute_cost_logistic` function computes the logistic cost for a given set of parameters (weights and bias). It iterates through each data point, computes the logistic function's output, and accumulates the cost based on the predicted values compared to the true labels.

3. **Plotting Decision Boundary:**
     The second plot illustrates two decision boundaries with different bias values ($b$). These boundaries separate the feature space into two regions corresponding to the two classes. The decision boundary with $b = -3$ is shown in blue, while the one with $b = -4$ is shown in magenta.

![plot-decision-boundary](https://github.com/UMMY87/Cost-Function-for-Logistic-Regression/assets/117314436/afa59c41-649e-4c93-8d14-d7130a586801)

4. **Cost Computation for Different Bias Values:**
     The code calculates and prints the logistic cost for two different bias values ($b = -3$ and $b = -4$) while keeping the weights constant. This comparison provides insights into how different bias values affect the logistic regression model's cost.

Overall, these visualizations and computations help in understanding logistic regression, including the representation of data points, computation of logistic cost, and visualization of decision boundaries. They are essential components for analyzing and evaluating logistic regression models.
