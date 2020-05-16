# Fintech BootCamp Project 1
 #   **Monte-Carlo Simulation & Portfolio Optimization**

![](https://raw.githubusercontent.com/MishraSubash/Working_Note-/master/Portfolio-Analysis-Overview2.png)


## Prepared By: 
  * **Kavin Minchala**
  * **Aljjohara Aloudan** 
  * **Subash Mishra** 
  * **Victor Martinez**

# Project Outline 
# Introduction : 
 The motivaiton for the project is to assess the financial performance of a stock portfolio that can be customized. 
 * Create an interface to customize the asset allocation of a portfolio and test the long term expected portfolio growth of that portfolio by using the Monte Carlo simulation to model the probability of the different outcomes.
 * Identify an optimal weight distribution for the different assets in the portfolio by determining the optimal Sharpe Ratio for a given portfolio.
 * Display how the results compare to a selected benchmark.
 
## A. Monte Carlo Simulation: 

#### Monte Carlo simulation involves using random number generators to simulate random effects. Simulating a historical prices for many times allows us to measure the variation just as we would if we took many samples of a real event. In this project we are using 30 years historical data to anlaysis risk-return pattern of an user desired portfolio. 

## B. Portfolio Optimization : 
#### Portfolio optimization is the method of selecting the best performing portfolio, out of the set of all portfolios being considered based on the amount of investment in each stock. Our project would select that portfolio which yeilds the highest sharpe ratio out of 5000 seperate portfolio meaning the highest expected return for desired level of risk. 

## Purpose of Project:

 * To run numerious simulation to analyse the underlying risk-retrun tradeoff of user desired stocks/portfolios. 
 
 * To get the optimum investment weight (Asset allocation) so that user could  pontentailly optimized portfolio to obtain highest sharpe ratio and expected to beat the market. 



## Hypothesis : 
#### It is possible to beat the market whne allocating optimum weight in a stock portfolio. 
#### The well diversified and properly allocated portfolio could possibly beat the market. 


## Data Source : 
#### To evaluate the project, we use Yahoo Finance as our primary data source. The reason using yahoo Finance is to get Adj Close. The adjusted close reflects stock dividens and stock splits which gives better idea of the overall value of stock and help making informed decision about trading stocks. 

## Timeframe :
#### In the first part of the project, we run numerious( user can opt any number of simulations) Monte-Carlo simulations based in 30 yrs historical data to priciously predict risk-return tradeoff and price flactuations of stocks in the portfolio.

## Questions and Data :

* What is the source and timeframe of data?
* Why benchmark is important? 
* Does larger number of stimulations give better idea to forcast?
* Can Users construct their own portfolio?
* Does portfolio optimization means neutral stragegy?


## Modeling and calculations :

##  A. Monte-Carlo Simualtion: 
#### We designed the project to fulfil user desire to construct portfolio. User can input any stock index of listed companies in the input panel, opt out time frame (by default it uses 30years) and number of simulations. Once user completed inputs, two separate Monte-Carlo simulations will run, one for stocks portfolio and other for benchmark. The simulations will allow to compare how user-selected portfolio perform with the benchmark over time. 

## B. Portfolio Optimization:

####  In this section, we code to find out the best performing portfolio among 5000 portfolios based on the highest Sharpe Ratio. The highest Sharpe ratio means the highest expected return for desired level of risk. Our code would able to locate and return the investment weight embedded in that best performing portfolio which means the portfolio which yields greatest Sharpe-ratio among 5000 possible outcomes. We call it as the most possible optimized portfolio. 

## Data Visualization :

#### This project comprises of several well simplified graphs. The graphs include scatter plot, line charts, boxplot, pie chart and many more. We understand the fact that visualizations make complex data easier to understand and makes easier to detect patters, trend, and outliers in the groups of data.  

## Summary and Conclusion :

#### The Monte-Carlo simulations is especially useful tool to model the probability of different outcomes. Here, in the above project our model was successful analyze the risk-return tradeoff between stocks and gives us clear idea to forecast future market prices. Moreover, the Portfolio optimization model allows user to guide for a selection of best performing financial assets. The model we developed helps user to select the best portfolio (asset distribution), out of the set of all portfolios being considered, according to the highest Sharpe ratio. Both Monte-Carlo simulation and Portfolio Optimization plays a considerable role within a strategic planning to predict the future stocks as well to get best performing portfolio so that investors possibly beat the market.  





