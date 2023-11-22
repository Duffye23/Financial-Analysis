Tasked with creating a portfolio of 3 stocks, the idea was to create a portfolio and pitch to a potential investor with the goal of having the investor commit 1 million dollars into our portfolio. After some time, we chose the following stocks: Electronic Arts Inc., Enphase Energy Inc., and Estee Lauder Companies Inc.</br>
We consolidated the following into a dataframe for simpler manipulation: Date, Company Symbol, Adjusted Close, and Symbol. The dataframe was then pivoted to show all three companies side by side.</br>
![image](https://github.com/Duffye23/Financial-Analysis/assets/58863493/a82665ca-9cca-45d2-b2e2-5b9255c571e9)</br>

We then plotted the dataframe over a timeline of 4 years to observe its trend.</br>
![image](https://github.com/Duffye23/Financial-Analysis/assets/58863493/4a861377-0e0d-45c4-9f86-4ecbea148320)</br>

We then added and plotted an Independent Value Check of the S&P 500 to compare gains versus our portfolio.</br>
![image](https://github.com/Duffye23/Financial-Analysis/assets/58863493/e7bc105c-36d4-4b66-9db3-cf74fd0fb184)</br>

From there we calculated the Max Sharp Ratio to forecast the returns on the portfolio. </br>
![image](https://github.com/Duffye23/Financial-Analysis/assets/58863493/ce1e8060-880f-49d9-bc92-2a12a9ef6f93)</br>
The Max sharp ratio for each was above 1, indicating strong risk-adjusted return on our investment portfolio.</br>

We then checked our portfolio for covariance. As our stocks were from different industries, the covariance was expectedly low. </br>
![image](https://github.com/Duffye23/Financial-Analysis/assets/58863493/57c3fa41-e09f-4c03-8a45-251b09b11a33)</br>

Finally, we built our Monte Carlo simulation for 3 factors: Simulated Rate of Return % for 30 days, Simulated RoR% for 1 year, and Simulated individual stock prices based on volatility and returns.</br>
Each simulation was run 1000 times.</br>






Contributing Authors: emmusic, MeloMaps, Ramatuay, alice43 and myself
