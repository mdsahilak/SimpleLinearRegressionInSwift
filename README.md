# Linear Regression In Swift

## A simple Regression Algorithm implemented in swift. 
### A swift struct is used to hold the value tables for x and y. The model's data table is filled during initialisation of the struct, by using the provided x and y values in the initializer parameters.
### The functions for calculating regression are provided within the struct. Except for the predict() calls, all calculations are done in the initializer and stored as model variables.
- - -
The Regression Coefficients: byx = ∑XY−nX¯Y¯ / ∑X2−nX¯2 and bxy = ∑XY−nX¯Y¯∑Y2−nY¯2.                                       

On the predict() function call, the algorithm uses regression equations of (x on y) and (y on x) to estimate the values. 

Regression Equation of X on Y -> (X - XMean) = b_XY(Y - YMean)                                                                

Regression Equation of Y on X -> (Y - YMean) = b_YX(X - XMean)
- - -
* The .swift file also contains a few examples of using the algorithm to predict values. 
* For example to convert a temp in celsius to farenheit, the algorithm is just provided a few sample values, a Dataset. When we call, .predict() with celsius value, the algorithm is able to predict the farenheit value(within a reasonable margin of error), even though the algorithm has no idea of the formula to convert temperatures. 
* As it does not use any specific formula, the same algorithm can be tried on miles to kilometres, predict house prices in locality based on population. Which is the point of machine learning - to be able to get such functionality by not explicitly coding them, but rather get the model to learn the relationship which enables generalised implementations.

If you would like to see another Classifier Algorithm in Swift, heres a [Generic Decision Tree Classifier](https://github.com/mdsahilak/DecisionTreeClassifier)

> Feedback appreciated. Thanks 😀
