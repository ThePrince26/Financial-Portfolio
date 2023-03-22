# Carbon VS Green : Which energy companies are the most profitable ? (BeCode Portfolio Optimization Challenge)

## Table of Contents

1. Summary
2. Visuals
3. Objectives 
4. Steps
5. Financial terms
6. Results & Insights
7. Further Developments
8. Limitations
9. Timeline
10. Personal Situation


## Summary
This project is a part of the Becode.org AI Bootcamp programme. My goal was to to create a dashboard with insights about 5 companies on the stock market based on scraped data provided in CSV format (see in the repo: data12.csv). The dashboard should be deployed with Public Tableau. The project is ended with presenting the data insights to the client.


## Objectives

In this project, I wanted to show how the various major events of our time - several financial, banking, energy and climate crises as well as waves of terrorist attacks and the worst pandemic in a century - impact energy companies on the financial markets. 

I decided to focus on five energy companies.


## Steps

1) I picked three large carbon companies (Exxon Mobil, Chevron and British Petroleum) and two renewable energy companies (General Electrics and NextEra Energy). Then, I downloaded the financial data of these five companies with Python (see Financial_Portfolio.ipynb) and focused on two variables in particular : "Close" & "Volume" (see financial Lingo).

2) I found it interesting to start my analysis from the day I was born (May 22, 1996) until today. I then created 5 graphs of these 5 companies on Tableau where we can visualize the evolution of the price of the shares as well as their trading volume over the last 26 years. 

3) After studying the graphs, I realized that there was a second analysis to be done, starting on September 1st 2000. In this second analysis, I calculated in Python the % price growth for each stock over the last 23 and a half years. I obtained interesting trends to help financial advisors inform their clients interested in investing in energy companies. 


## Financial terms

The understanding of two main financial metrics is important for this project.

1) Close

"Close" refers to the last traded price of the asset or security at the end of a particular trading day. This is an important metric as it provides information on the price at which the asset was last traded and can be used to calculate changes in the asset's price over time.

2) Volume

"Volume" refers to the total number of shares or contracts traded for a particular asset or security during a given trading day. It measures the level of market activity and is an important indicator of market liquidity, as higher trading volumes typically indicate greater liquidity.

In a financial dataframe, "Close" and "Volume" would typically be columns that contain the closing price and trading volume data for each trading day, respectively. This data can be used for a variety of financial analysis purposes, such as technical analysis, trend analysis, and risk management.


## Visuals

![image](https://user-images.githubusercontent.com/119889349/226913357-3dbb0d1c-38f9-4c37-b898-0c28ff96ccff.png)

URL link : https://public.tableau.com/app/profile/augustin.carbonnelle/viz/FinancialPortfolioDataAnalysis/FinancialPortfolio

##  Results & Insights

| Company           | Growth    |
|-------------------|:---------:|
| British Petroleum | -37.26%   |
| Chevron           | +259.75%  |
| ExxonMobil        | +145.76%  |
| General Electrics | -74.10%   |
| NextEra Energy    | +1008.80% |

With these results, we have the following insights ;

* Chevron and ExxonMobil have performed very well.
* British Petroleum and General electrics have performed poorly.
* NextEra Energy's stock price has been spectacular.


## Further Developments

* Visualize the % growth in Tableau
* Create more interactive graphs
* Craft a visually stunning dashboard
* Perform deeper insights (What are the reasons behind British Petroleum's and General Electrics' underperformance ? Why has NextEra Energy risen so much ? What explains the big collapse and uptick on some stocks on some particular moments ?)


## Limitations

* Only 5 companies scrapped -> Need to get more data in order to make more definitive, accurate and general conclusions.
* Need to write a more elaborate code & analyse stocks with more variables to answer more complex questions.


## Timeline

I worked on this project during 8 working days. 


## Personal Situation

I am currently participating in the Becode.org AI Bootcamp to upskill into a career in data analytics and data science. 
I look forward to work on media, environmental, poltical and geo-strategic projects, for I have a wide interest in cinema, litterature, politics and philosophy;
That's why I am driven to put my passions front and center in order to provide valuable service for any private or governmental organization. 

Feel free to follow/contact me on :

https://www.linkedin.com/in/augustin-carbonnelle-b4551b24/
