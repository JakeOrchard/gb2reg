This project is no longer maintained. 

# gb2reg

GB2 Regression Stata Package

This is a Stata package that fits a generalized beta of the second kind (GB2) model to data. The standard linear regression model typically assumes that the errors are independently and identically distributed. The corresponding ordinary least squares (OLS) estimator will yield the best linear approximation of the conditional mean. This regression method, which uses the GB2 distribution, can accommodate situations in which the conditional mean, variance and skewness of a variable of interest may vary as a function of independent variables. 

Installation

The development version from github:

net install gb2reg, from(https://raw.githubusercontent.com/jakesurf/gb2reg/master/) force
