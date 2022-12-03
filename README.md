# Linear regression
Multiple methods for linear regression

**Goal** : We try to predict a real-valued output y (dependent variable or target) given a vector of real-valued inputs X (independent variables, explanatory variables, or covariates).

We can formulate the problem of linear regression in 2 ways :

- without regularization $$\text{argmin}_{w} \frac{1}{2} \Vert Xw - y \Vert_2^{2}$$
- with regularization $$\text{argmin}_{w} \frac{1}{2} \Vert Xw - y \Vert_2^{2} + \lambda R(w)$$

In the notebook, we will focus on **linear regression without regularization**. Nevertheless, we will briefly mention it.

Here is a quick overview of the different methods we will apply :

- Method 1 : Closed-form

- Method 2 : QR decomposition

- Method 3 : Moore-Penrose inverse

- Method 4 : Gradient descent

- Method 5 : Stochastic Gradient Descent
