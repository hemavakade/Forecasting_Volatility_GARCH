# Project in Advanced statistics.

This project was done as part of my Advanced statistics course in my Data Science Masters curriculum. 

The goal of the project was to gain an understanding of Advanced Time Series modeling for Financial data.

The data set is the closing prices for S&P 500 stock index obtained from Yahoo finance. I
used GARCH(1,1) to model the volatility of the returns of the closing prices. The final model had an AIC of
-6.6856 and RMSE of 0.08.

# Tools

I used R for this project and explored the usage of `rugarch` package.

# References

- Engle, Robert F. “Autoregressive conditional heteroscedasticity with estimates of the variance of United
Kingdom inflation.” Econometrica: Journal of the Econometric Society (1982): 987-1007.
- http://faculty.washington.edu/ezivot/econ589/ch18-garch.pdf
- Bollerslev, Tim. “Generalized autoregressive conditional heteroskedasticity.” Journal of econometrics 31.3
(1986): 307-327.
- Rugarch Vignette, https://cran.r-project.org/web/packages/rugarch/vignettes/Introduction_to_the_rugarch_package.pdf
- Rugarch Vignette Example, http://unstarched.net/wp-content/uploads/2013/06/an-example-in-rugarch.pdf
- Volatility for Emerging markets, https://www.linkedin.com/pulse/stochastic-volatility-forecasting-emerging-markets-swati-mital

# Future Work.

Financial time series modeling requires domain knowledge, in that it is very helpful to understand the terms and translate it into code. I would like to explore the differen flavors of GARCH and gain more domain knowledge. I would also like to use LSTMs with the data.
