# USA-Stock-Market-prediction-using-Financial-Fundamental-data
Repository contains USA Stock Market prediction using Financial Fundamental data which involved EDA, Statistical Analysis and Model Building
## Business problem we are trying to solve

### Motivation Behind Choosing this project
There is too much information in the financial statements of the company and seeing each company's financial data  (balance sheet, cash flow, income statements & financial ratios) before making  investment decisions is a challenging task . 

### How is this problem being currently solved?

Big investor/ rating agencies have their extensive own research team that study each company’s financial statements in detail and figure out the best companies to invest in 

Investors who can’t afford such detailed analysis , generally rely on few important financial metrics like Price/Earning ratio , EBITDA etc as a rule of thumb before making investment decisions. But such methods are only heuristics and not guaranteed to work.

### How are we trying to solve this problem effectively?
We are trying to build a model which takes around 200+ financial indicators of a company & predicts if we as an investor should buy the stock or not. This would automate the whole investing process which currently is very research intensive or rely on guesswork as mentioned above

### Business Impact of this project
Investors could use this tool to make informed investment decisions with ease. This would specially empower the small investor which can’t afford extensive research.

### Data Set
Dataset contains 200+ financial indicator features, that are commonly found in the 10-K filings each publicly traded company releases yearly, for a lot of US stocks (on average, 4000 stocks are listed in each year dataset). We have five year of data (2014-2018). So, a total of 22,000 rows approx. Since we are predicting for 2 major classifications the consecutive years, we have merged the available 5 years data into a single data frame.

Success of this model depends on 2 major classifications that are said to be class1 and class 0.For each stock, if the class = 1. From a trading perspective, the 1 identifies  those stocks that an hypothetical trader should BUY at the start of the year and sell at the end of the year for a profit. For each stock, if the class = 0. From a trading perspective, the 0 identifies those stocks that an hypothetical trader should NOT BUY, since their value will decrease, meaning a loss of capital

### EDA
Univariate, Bivariate and Multivariate Analysis were performed to bring out important aspects of data into focus for further analysis. Some of the highlights from EDA are listed below.

![counter_plot_of_class](https://user-images.githubusercontent.com/62056802/110202551-62ec2b80-7e8f-11eb-875e-dfcb0cfb3746.PNG)

![Median net income per sector](https://user-images.githubusercontent.com/62056802/110202570-929b3380-7e8f-11eb-8f78-38285d5c7dd1.PNG)

#### Inference
a. We can infer that median net income per share of utilities and financial sectors are higher than the others.
b. Energy and Technology have lower net income per share compared to other sectors.
c. Healthcare has negative net income per share


![Sector wise market capital of stocks](https://user-images.githubusercontent.com/62056802/110202597-d0985780-7e8f-11eb-8537-ab7577ed5bb0.PNG)

#### Inference
As per the graph we can see that Healthcare and financial services companies seem to have a high market capital and sectors like basic material, communication services, consumer defense, real estate, utilities, companies with low market capital are more in number.



