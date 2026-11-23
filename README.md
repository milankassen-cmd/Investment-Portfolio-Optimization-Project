<h1> Investment Portfolio Optimization Project </h1>

<h2> Introduction </h2>
This project aims to assign how much weight or the percentage each asset would take up in our hypothetical portfolio. It will uses linear programming and Modern Portfolio Theory to determine how much of each stock/asset the portfolio should have based on the risk and returns. This project would hypothetically be good for investment analysts and portfolio managers.

<h2> Objective </h2>
The objective of this project which uses Modern Portfolio Theory and Linear Programming is to minimize the risks and maximize the returns of our portfolio by adjusting/optimizing the percentage each asset/stock would hold in our portfolio. The assets are chosen arbitrarily and are chosen across different industries. 

<h2> Data and Packages </h2>
<b> Packages: </b> numpy, pandas, plotly, scipy, yfinance <br>
<b> Data Source: </b> data obtained from yfinance library

<h2> Data Cleaning and EDA </h2>
Not much cleaning of the data was needed as the yfinance library uses real data that has already been cleaned and structed accordingly. Only the Close Price column was needed again for this project.

<h2> Conclusion </h2>
After performing all the optimization techniques the asset with the highest weight assigned was Berkshire Hathaway, which makes up about 50% of the portfolio. This makes sense as this asset is already diversified and structed for good returns and low risk. Rolls-Royce, Disney and AstraZeneca make up less than 1% as these assets do not yield high returns, are susceptible to market shocks and are in niche industries. The data used is live and so changes in percentages will change on a daily basis. This project was a hypothetical portfolio creation and optimization that uses real data from real assets that are up-to-date and each individual could change the assets used. There are shortfalls as Modern Portfolio Theory is an entry level optimization technique - other techniques like the Black-Litterman Model can be used by more experienced analysts to optimize their portfolio for personal use or client use, this adds complexity but is a more intuitive model with more stable weights.
