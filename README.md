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

### DATASET
Dataset contains 200+ financial indicator features, that are commonly found in the 10-K filings each publicly traded company releases yearly, for a lot of US stocks (on average, 4000 stocks are listed in each year dataset). We have five year of data (2014-2018). So, a total of 22,000 rows approx. Since we are predicting for 2 major classifications the consecutive years, we have merged the available 5 years data into a single data frame.
