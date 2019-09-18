# Linear Regression In Swift

## A simple Regression Algorithm implemented in swift. 
### The code uses a swift struct to hold the value tables of x and y. The functions for calculating regression are provided within the struct.
### The table is filled during initialisation of the struct, by using the provided x and y values.
### The Regression Coefficients: byx = ∑XY−nX¯Y¯ / ∑X2−nX¯2 and bxy = ∑XY−nX¯Y¯∑Y2−nY¯2.                                       On the predict() function call, the algorithm uses regression equations of x on y and y on x to estimate the values.           Regression Equation of X on Y -> (X - XMean) = b_XY(Y - YMean)                                                                  Regression Equation of Y on X -> (Y - YMean) = b_YX(X - XMean)

> The swift file also contains a few examples of using the algorithm to predict values. For example to convert a temp in celsius to farenheit, the algorithm is just provided a few sample values, a Dataset. When we call, .predict with celsius value, the algorithm is able to predict the farenheit value thats pretty close to the actual value, even though the algorithm has no idea of the formula to convert temperatures. As it does not use any specific formula, the same algorithm can be tried on miles to kilometres, predict house prices in locality based on population or anything really, which is the essence of machine learning to be able to get such functionality by not explicitly not coding them in which enables generalised implementation.
