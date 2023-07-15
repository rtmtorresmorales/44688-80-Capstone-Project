# 44688-80-Capstone-Project
# Digital Asset Investment Analysis and Predictive Modelling Capstone Project Report
#Abstract 
This article presents a preliminary proposition for investment analysis for a digital asset. The analysis is based on historical data of the bitcoin price for the years 2015 to 2023.  Correlation analysis is performed, and seasonality decomposition is completed to identify trends, price movements and low and high buying seasons for this digital asset.  Based on correlation and residuals analysis an initial predictive model for the Bitcoin price is proposed using ARIMA methodology.  In summary, general findings showed seasonality of the buying and selling trends at the end of each year analyzed and correlation was reached, setting up the scenario for the presentation of a bitcoin price predictive model.  The tools used for this project included Jupiter Notebook, Latex using Oleaf, MS Word, Acrobat, Kaggle and CoinmarketCap Data Sets and Crypto and modelling was design using Pyhton and its libraries.  All details, steps, files and code for the development of this project is available in https://github.com/rtmtorresmorales/44688-80-Capstone-Project, [6]
The planned domain is Natural language processing and visualization to demonstrate trends on investment options, [5]. The goal is to analyze sentiment analysis of experts, investors and institutional investment firms. Based on current world events and the generalization of the cryptocurrencies, particularly the bitcoin, I would like to analyze investment trends to preserve capital.  I will use Kaggle data sources to obtained data sets to analyze financial trends and compare to financial reports and determine the sentiment or opinions of experts on this field .  The process will include the following steps: 
# Introduction
1. Explore for possible investment analysis scenarios
2. Search for data sources and save it to computer in CSV and MS Excel formats
3. Use python to organize and clean
4. Select appropriate data sources and columns
5. Design and run analysis model
6. Use Tableau to present visualization of relevant results
7. Present project report
# Project Goals
Based on current world events and the proliferation of the digital currencies, it is beneficial to analyze investment trends to preserve capital and enhance return on investments for such instruments, [2,3,7].The project is intended to: 

1. review forecasting and predictive modelling for the and investment instruments

2. review of historical trends of the bitcoin for the period from 2015 to 2023.  

3. generate a predictive tool for future applications to other types of investments and asset classes

This tool may identified parameters that influence the market price of the digital currency.  This exercise may be useful for the individual, institutional, or highly speculative investor.   
# Definitions
The definitions of important data attributes.
               date = date of transaction

              Open = value of bitcoin when market open

              Close = value of bitcoin when market close

              High =   highest value of bitcoin on a trading day

              Low =    lowest value of bitcoin on a trading day

              Volume = total shares traded during a trading day

              MarketCap = total value in dollars per trading day.

# The process
Steps will include:

Step 0: Design, organization, and initial setup

Step 1: Installing and Setting up required analysis tools			       

Step 2 Accessing libraries, analytical, statistical tools

Step 3:  Access Crypto Library

Step 4: Accessing Data sets - pull data from start of 2015 to present day

Step 5:  Main object definition and accessing historical bitcoin prices from bitinfocharts

Step 6: Additional historical bitcoin data from coinmarketcap

Step 7: Graphs configurations for Cryto Historical trends 2015 to 2023

Step 8: Resampling frequencies on monthly price, annual and quarterly

Step 9: Graphs configurations for Crypto frequencies

Step 10: Graphs configurations for seasonal data decomposition

Step 11 Seasonality analysis parameters definition

Step 12 Seasonality analysis for bitcoin market price per month, decomposition and visualization of results

 Step 13 Approximation of parameters using correlation plots. 

Step 14 Parameters for approximation definition using correlation.

Step 15 Model Selection and fitting

Step 16 STL-correlational decomposition and visualization of correlational results and residuals

Step 17 Model prediction

# Conclusions
From the historical data and inference analysis, four peak price points occurred in 2018, 2020, 2021 and 2022. The moving average showed the higher prices by years 2021 and 2022.  The prices of cryptocurrencies showed a tendency of having market value under pressure for months of September and October of every year.  This showed a downward trend on the values of the digital asset. Then after these periods of overselling, upward trends appear to present until the end of each year.  By December of every year, a buying rally reached a peak, as well as the value of the asset.

Based on seasonality analysis and statistical analysis, seasonality decomposition resulted in a clear bitcoin price seasonality by the end of each year.  The correlation analysis shows dependency and correlation on the results of the proposed model and the lagging values, therefore promoting the proposition of a predictive or forecasting model for the bitcoin prices.  As per the predictive model, the multi-line chart shows demonstrate the correlation among the actual bitcoin prices and the predicted values. 

# Ethical considerations and limitations

In general, financial investing may be a lucrative way of generating wealth with appropriate ethical compass.  This tends to diminish when greed comes into play.  Strategic investment planning is put aside for the quick and relentless return.  Investors tendencies move toward no traditional assets, such as cryptocurrencies that has no clear economic underlying in an unregulated investment environment.  This open up various ethical issues over this asset class, such as manipulation, unqualified investors, illegal uses of the asset and erratic investment behavior, [1].  Therefore correlation analysis needs a deeper review to determine an extract some of the previously mentioned ethical considerations, that may impose limitations on the predictive model, like some outliers and incongruities.

# Recommendations 

The investment asset shows a high level of volatility, a seasonal trading patterns that alter the price values, typically by the end of each year and perhaps showing some investor behavioral impulse to increase selling and buying the assets before and after the buying season hits.  Enhancing the correlation analysis process to filter out outliers and erratic trends is highly recommended.  In addition, further analysis and predictive modelling may support cryptocurrencies portfolio optimization techniques, combing various digital assets and their parameters, volatility and investment risk management based on seasonality, enhance performance and financial returns.

# References
1. https://notebook.community/dashee87/blogScripts/Jupyter/2018-02-11-analysing-
the-factors-that-influence-cryptocurrency-prices-with-cryptory
2. Cryptocurrencies analysis and forecasting, https://www.kaggle.com/code/vovchuk/cryptocurrencies-
analysis-and-forecasting
10 R. Torres.
3. Chein, J.: Analysis of bitcoin price prediction using machine learning. AlphaSene
(2023)
4. Kashettar, S.: 5 best crypto prediction site tools,
https://www.analyticsinsight.net/5-best-crypto-prediction-site-tools/
5. Sheynin, N.: 3 ways to apply natural language processing (nlp) in financial research.
AlphaSene (2022)
6. Torres, R.: 44688-80-capstone-project, https://github.com/rtmtorresmorales/44688-
80-Capstone-Project
7. Vimalachandran, A., Jayachandran, T.: The financial crash of 2020 and the retail
trader’s boon: a correlation between sentiment and technical analysis. SN Business
