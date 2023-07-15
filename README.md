### OLS Regression of a rotated Bivariate Normal sample
Comparing intuition and reality in estimating lines of best fit.

If we:
- generate *n* observations, *X ~ Normal(0,1)* and *Y ~ Normal(0,0.2)* [where the second value represents standard deviation], 
- plot on the Cartesian coordinates *(x,y)* and then rotate by 45 degrees, 
- then perform regression using ordinary least squares (OLS),  

what is the expected value of *b1* (the estimated coefficient of *x*)?

As we will see (or may be obvious already), the intuitive response tends to be (because we have rotated by 45 degrees) that the answer is $E[b_1]=1$

This notebook examines whether or not this is in fact so.

(Problem sourced from Twitter user [@quantian1], I have amended the standard deviation used for $Y$ to better illustrate differences.)

[@quantian1]: https://twitter.com/quantian1/status/1673358773178585091?s=20
