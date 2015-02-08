# Statistical Learning - Chapter 2

## Exercises
### Conceptual
1. For each of parts (a) through (d), indicate whether we would generally expect the performance of a flexible statistical learning method to be better or worse than an inflexible method. Justify your answer.
    - (a) Sample size *n* is extremely large, and number of perdictors *p* is small.
       - Flexible is better. A flexible model will allow us to take full advantage of our large sample size.
    - (b) Number of predictors *p* is extremely large, and number of observations *n* is small.
        -   Flexible is worse. The flexible model will cause overfitting due to our small sample size.
    - (c) The relationship between the predictors and response is highly non-linear.
        - flexible is better. An inflexible method will miss the non-linearity effect.
    - (d) The variance of the error terms, i.e. $sigma^{2}=Var(\epsilon)$, is extremely high.
        - Flexible is worse. A flexible method will fit the random error closely, modelling the noise rather than the signal.

2. Explain whether each scenario is a classification or regression problem, and indicate whether we are most interested in inference or prediction. Finaly, provide *n* and *p*.
    - (a) Regression, Inference. n = 500, p = 3
    - (b) Classification, Prediction. n = 20, p = 13 
    - (c) Regression, Prediction. n = 52, p = 3. 

3.  Bias-variance decomposition
    - ![image](/images/ex2_q3.jpg)
    - 
4. 




