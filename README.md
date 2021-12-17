# Linear-Regression with Python Code

![markdown](https://miro.medium.com/max/1200/1*quSxcHc0ib4nbtj7TFH6gw.png)

## Regression
Regression is one of the most important fields in statistics and machine learning. There are many regression methods available. Linear regression is one of them

## What is Regression ?
Regression is searches for relationships betweens among variables.
For example: relationship between *incomes* and *happy*
In this example,
  * *incomes* is called **independent variables, inputs or predictor**, usually denoted as variable x or vector x=(x1,x2,..) if have more than one input variable
  * *happy* is called **dependent variables, outputs or reponses**, usually denoted as y

You need to find a function that maps some variables to others
Regression problems usually have one continous and unbounded dependent variable. However the inputs can be continous, discrete or even catagorial data such as gener, nationality, brand, and so on.

## When do you need regression
  * when you want to know how several variables are related. Example: how experience or gender impact salaries
  * Regression is also useful when you want to forecase a response using a new set of prefictors. Example: predict electricity consumption of a household given temperature
 
## Linear Regression
Is is the simples regression methods
### Problem Formulation
𝑦 = 𝛽₀ + 𝛽₁𝑥₁ + ⋯ + 𝛽ᵣ𝑥ᵣ + 𝜀
  * y is output
  * x = (x1, x2,...,xr) is input
  * e is random error

Linear regression calculates the estimators of the regression coefficinets or predicted weights, denoted with b0, b1,...,br. They define the estimated regression function 𝑓(𝐱) = 𝑏₀ + 𝑏₁𝑥₁ + ⋯ + 𝑏ᵣ𝑥ᵣ with the goal that the different 𝑦ᵢ - 𝑓(𝐱ᵢ) is minimum

To get the best weights, you usually minimiza the sum of squared residuals (SSR) for all observation i=1,2,...,n.

SSR = Σᵢ(𝑦ᵢ - 𝑓(𝐱ᵢ))²

This approach is called the method of ordinary least square

### Simple linear regression
It is the simplest case of linear regression with a single independent variable 

![markdown](https://files.realpython.com/media/fig-lin-reg.a506035b654a.png)

### Multiple linear regression
In this case we have 2 or more variables
