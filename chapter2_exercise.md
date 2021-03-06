1. Will flexible be better?  
  a. Better - because we have a lot of data  
  b. Worse - because we don't have enough data and might overfit with flexible approach  
  c. Better - flexible models can represent better non-linear relations  
  d. Worse - flexible model would learn more noise in the data  

2. Characterize scenarios  
  a. Regression, inference, n = 500, p = 3  
  b. Classification, prediction, n = 20, p = 13  
  c. Regression, prediction, n = 52, p = 3  

3. Bias-Variance tradeoff - see img/bias_variance.png  

4. Real-life applications  
  a. Classification - approving credit in a bank, predicting whether cancer is benign or malignant, classifying images  
  b. Regression - predicting the price of a house, predicting stock price, predicting salary  
  c. Cluster analysis - clustering customers into groups by buying behavior, 

5. More flexible approach can learn highly non-linear relations better. If the data is highly non-linear then we would prefer more flexible model. On the other side if the data is close to linear then we would prefer less flexible approach to avoid overfitting. The amount of data is also important - for more flexible model we would like to have more data. If we are interested in inference then we would prefer a less flexible model.

6. A parametric model learns a set of parameters e.g. linear regression learns a set of weights and bias.  
A non-parametric model is not described in terms of parameters.  

| Model | Advantages | Disadvantages |
|------ | ---------- | ------------- |
| parametric | easier to estimate | biased |
| non-parametric | not biased | large number of observations |

7. d. We would prefer the K to be small because we want very flexible model in this case.
