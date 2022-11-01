# Group_13

As a team we are trying to aid our first client, Brandyn, in his home search
We are acting as a consultancy that is establishing a process to analyze housing data
Our first step is to collect foundational knowledge about the housing market

Key areas of interest:
Alpharetta
Brookhaven
Buckhead
North Druid Hills
Old 4th Ward
Sandy Springs
Suwanee
Smyrna

Initial Assumption(s): 
Low inventory contributed to the recent home sale boom the last two years.  We feel there is a shift in the market that can be timed by the buyer to gain an advantage over the seller in negotiating the final price.

Our Goal → Is inventory related to housing prices?
We want to help our client determine any correlation between low inventory and final sales price.  Thus…will waiting for periods of high inventory allow for a lower sale price and increased equity??

Our Hypothesis: Is there a correlation between median sales prices and housing inventory levels?
The Null: Increasing inventories has no effect on median sales prices at all
Alternative: Decreased inventory leads to higher median sales prices.

Analysis Approach
Identifying Data Source: Flat file CSV was downloaded from Redfin.com
10 years of monthly home sale price and inventory data
Selected 8 regions within Atlanta to analyze

Plot Everything: Scatter plots based on inventory and median sales price
Pairplots via the Seaborn package
Coefficient correlations 
Sliced data by years and by regions

Test Hypothesis: Looked for patterns and trends in the plots
Evaluated null and alternative hypothesis

Initial Learnings:
Data Quality
Outliers were removed
Dataset was already manipulated to be average median data
This may make it harder to identify patterns/trends
Economic Factors
House pricing data isn't adjusted for inflation over time

Conclusions:
We are rejecting the Null Hypothesis of:
Increasing inventories and it has no effect on median sales prices.
The absolute value of our Pearson coefficients are between 0.4 and 0.79, indicating Moderate to High Correlation
Inverse correlation between inventory and median sales price
Further research is needed
Old 4th Ward and Brookhaven may be ideal places to begin the house hunt

