# Financial-Data-Analysis-Project

Risk Management and Risk Modelling are becoming critical day by day for most of the businesses esp. those in Banking and finance. Sub-prime crisis, 2008 has made adaptation of risk measuring tools faster in the finance world. In this study, we analyze and compare the results of various methods used in forecasting Value at Risk (VaR) with three market indices. Using around ten years of the daily return data from on S&P 500, Nifty 50 and S&P/TSX composite index, we find the Value at Risk estimated by various models and strategies at offset of global equities market steep downfall during March,2020 due to pandemic. 

After the analysis, it is found that most approaches perform inadequately, although several models gave acceptable VaR figures considering what happened later in the month of March,2020. The accuracy of VaR estimation depends on the distribution of the data and hence the methods used. VaR is certainly a better risk monitoring measure that historical volatility, etc. The predictive performance of several recently advanced and some new VaR models has been examined. The majority of these suffer from excessive VaR violations, implying an underestimation of market risk. 


### Conclusion 
In the analysis, we were trying to calculate one day and 15 day VaR for three indices using various methods from RiskMetrics to Extreme Value Theory. The aim of this analysis was to see which methods were signaling a huge drawdown in March 2020 as due to onset of pandemic , there was a sharp fall in the global markets. Emerging markets such as India went through more than 40% correction while developed markets like USA and Canada fell almost 20-30% from February 2020 levels. If a fund manager were relying on the Value-at-Risk measure for monitoring the risk in his 100 units portfolio in each of three markets on 1st March 2020, what would each of the methods used in VaR calculations were signaling about riskiness of 
his portfolio. 
From the results we observed that every method gave different estimates for Value at Risk for one day and 15 day estimates. The Indian market index ,Nifty 50 fell the most post 1st March 2020 and this has been reflected in estimation of VaR by almost all methods. The GARCH(1,1) with Student t-distribution gave most accurate estimates about what to come in future. There are substantial differences among different approaches. This is not surprising because there exists substantial uncertainty in estimating tail behavior of 
a statistical distribution. Since there is no true VaR available to compare the accuracy of different approaches, we recommend that one applies several methods to gain insight into the range of VaR. In practice, VaR prediction is hampered by the fact that financial returns exhibit ‘‘nonstandard’’ statistical properties. Specifically, they are not independently and identically distributed (iid) and, moreover, they are not normally distributed. This is reflected by three widely reported stylized facts: 

(i) volatility clustering, indicated by high autocorrelation of absolute and squared returns; 

(ii) substantial kurtosis, that is, the density of the unconditional return distribution is more peaked around the center and possesses much fatter tails than the normal density; and 

(iii) mild skewness of the returns, possibly of a time-varying nature. As a consequence, ‘‘standard’’ methods, based on the assumption of iid-ness and normality, tend not to suffice, which has led to various alternative strategies for VaR prediction. 
