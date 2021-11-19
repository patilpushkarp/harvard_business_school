# Multiple Regression

## Introduction

### Introducing Multiple Regression

- **"Most management problems are too complex to be completely described by the interactions between only two variables. Incorporating multiple independent variables can give managers a more accurate mathematical representation of their business."**
- It is necessary to factor any relationship between two or more independent variables in regression analysis. This can be achieved by multiple regression. 
- **" In multiple regression, we adapt what we know about regression with one independent variable — often called simple regression — to situations in which we take into account the influence of several variables."**
- Visualization and graphical representation become essentially impossible beyond three variables.
- **"As managers, almost any quantity we wish to study will be influenced by more than one variable: to construct an accurate model of a business' dynamics, we'll usually need several variables. Multiple regression is an essential and powerful management tool for analyzing these situations."**

#### Summary

- **"Multiple regression is an extension of simple regression that allows us to analyze the relationships between multiple independent variables and a dependent variable. Relationships among independent variables complicate multivariate regression. With more than two independent variables, graphing multivariable relationships is impossible, so we must proceed with caution and conduct additional analyses to identify patterns."**
![Summary](./summary_introduction_multiple_regression.png)

---

## Adapting Basic Concepts

### Interpreting the Multiple Regression Equation

- **"In general, the linear equation for a regression model with k different variables has the form below. Since the coefficients we obtain from the data are just estimates, we must distinguish between the idealized equation that represents the "true" relationship and the regression line that estimates that relationship. To express that even the "true" equation does not fit perfectly, we include an error term in the idealized equation."**
![General Regression Equation](./general_regression_equation.png)
- **"The coefficient in the simple regression and the coefficient in the multiple regression have very different meanings."** In the simple regression equation of dependent variable versus independent variable, we interpret the coefficien of slope in the following way: for a unit increase in the independent variable, we expect dependent variable to increase/decrease by the coefficient of slope (positive/negative).
- We describe the above change in dependent variable as gross effect. It is an average computed over the range of variation of all other factors that influence dependent variable.
- In multiple regression, the coefficient for an independent variable tells us that for every unit change in independent variable, dependent variable change by coefficient provided other independent variables remain constant.
- We describe the above change in dependent variable as net effect. It is the effect of the independent variable under consideration over dependent variable controlling other independent variables.
- **"A coefficient is "net" with respect to all variables included in the regression, but "gross" with respect to all omitted variables. An included variable may be picking up the effects on price of a variable that is not included in the model."**
- **"For each independent variable, we must inspect its p-value in the regression output to make sure that its relationship with the dependent variable is significant."**

#### Summary

- **"We use multiple regression to understand the structure of relationships between multiple variables and a dependent variable, and to forecast values of the dependent variable. A coefficient for an independent variable in a regression equation characterizes the net relationship between the independent variable and the dependent variable: the effect of the independent variable on the dependent variable when we control for the other independent variables included in the regression."**

### Residual Analysis

- **"The regression equation with two independent variables defines a plane that passes through the data. The residuals — the differences between the actual and predicted dependent variable in the data set — are the vertical distances from the regression plane to the data points."**
- **"As in simple regression, these vertical distances are known as residuals or errors. The regression plane is the plane that "best fits" the data in the sense that it is the plane for which the sum of the squared errors is minimized."**
- **"We can plot the residuals against the values of each independent variable to look for patterns that could indicate that our linear regression model is inadequate in some way."**
- **"When linear regression is a good model for the relationships studied, each of the residual plots should reveal a random distribution of the residuals. The distribution should be normal, with mean zero and fixed variance."**
- **"The residual plot against distance in the multiple regression looks different from the residual plot against distance in the simple regression. They represent different concepts: the first gives insight into the net relationship and the second gives insight into the gross relationship."**
- **"Because residual plots always involve only two variables — the magnitude of the residual and one of the independent variables — they provide an indispensable visual tool for detecting patterns such as heteroskedasticity and non-linearity in regressions with multiple independent variables."**

#### Summary

- **"The residuals, or errors, are the differences between the actual values of the dependent variable and the predicted values of the dependent variable. For a regression with two independent variables, the residuals are the vertical distances from the regression plane to the data points. We can graph a residual plot for each independent variable to help identify patterns such as heteroskedasticity or non-linearity."**
![Summary](./summary_multiple_resgression_residuals.png)

