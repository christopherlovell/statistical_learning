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
    - Squared bias: As flexibility increases the inherent inaccuracy of the model decreases.
    - Variance: Variance is a measure of how much the fit would change if the training sample was changed. For an inflexible model this change will be minimal, however a flexible model will be fit to the noise in the original sample and will change a lot.
    - Training error: A more flexible model will fit the training data more closely, including the random error.
    - Test error: The fit will reach a minimum at th random error value where the flexibility of the model allows it to resemble the underlying trend, but is not so flexible that it then overfit to the noise.
    - Bayes(irreducible) error: Does not change with flexibility. 
4. Real life applications for statistical learning:
    - (a) Classification
        - 




