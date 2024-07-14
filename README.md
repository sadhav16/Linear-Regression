# Linear-Regression
This project features a machine learning model developed to analyze and predict patterns in complex datasets. Through advanced algorithms and data processing techniques, this model aims to deliver precise and actionable insights. Explore the code, datasets, and documentation to learn more about the model's capabilities.


**Description**

The notebook file demonstrates how to implement linear regression using a Advertisement dataset. 
The steps include loading the data, preprocessing, training the model, and predicting values.

The notebook requires the following Python packages:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib

**Modify Data Path if Necessary:**

  If your data is saved in a different location, update the path in the notebook code where the data is loaded.


The notebook includes code to predict values using the trained linear regression model.

The implementation of linear regression from scratch has also been completed using the matrix method.
This involves leveraging linear algebra to compute the best-fit line by minimizing the sum of squared errors.
**Optimization using the Normal Equation**
The normal equation provides a direct way to find the optimal model parameters without iterative optimization. The normal equation is given by:



where:

𝜃:
θ is the vector of model parameters (coefficients).

𝑋:
X is the input data matrix with an added column of ones for the intercept term.

𝑦:
y is the vector of target values.


>Ensure to run all cells to see the predictions.
