The Data Portfolio — Big Mac Index Analysis

Objective
This project uses The Economist's Big Mac Index to test Purchasing Power Parity across countries and measure how far exchange rates sit from PPP-implied levels.

Methodology
Loaded the Big Mac Index panel dataset directly from The Economist's GitHub repository, covering 57 countries across 45 time periods from April 2000 to July 2026
Extracted three distinct data structures from the same dataset, a cross-sectional snapshot, a single-country time series, and the full panel
Computed implied PPP exchange rates from local Big Mac prices and the US benchmark price, then derived a valuation percentage for each country against the US dollar
Diagnosed missing data patterns across the panel and classified the mechanism behind each gap, including Russia's exit from the index as MNAR (missing not at random) due to its 2022 McDonald's withdrawal
Built two visualizations, a horizontal bar chart ranking currency valuations for the July 2024 cross-section and a multi-country time series tracking valuation trends over the full sample

Key Findings
The July 2024 cross-section (54 countries) shows Switzerland as the most overvalued currency in the index, priced 41.8% above PPP-implied fair value. The distribution skews heavily the other way, with a median valuation of -20.7% and only 6 of 54 countries priced above the US. Japan trades undervalued across most of the sample. These results are consistent with the broader pattern that high-income countries with expensive non-tradeable inputs, rent, wages, and local taxes, tend to show sustained overvaluation on this measure, while countries with lower local services costs skew undervalued.
