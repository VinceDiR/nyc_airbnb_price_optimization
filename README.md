# Predicting Funding Rounds for Crypto/Blockchain Startups #
### By: Nate DiRenzo

## Statement of Need:
In recent years, crytpocurrency and blockchain startups in the US have received a massive influx of venture capital. In 2021 alone, this number exceeded $33 Billion-- more than all other years combined. Among the firms leading the way are firms such as [Paradigm](https://techcrunch.com/2021/11/15/crypto-vc-firm-paradigm-debuts-monster-2-5-billion-fund/) and [Andreessen Horowitz](https://www.coindesk.com/business/2022/01/20/andreessen-horowitz-looks-to-raise-45b-for-new-crypto-funds-report/), both of which have committed over $2 billion to the space in 2021 with more to come in 2022.

Despite this surge in interest and popularity for all things blockchain and crypto among consumers and venture capitalists alike, the space is young, and not well understood. Here, we will evaluate a dataset taken from Crunchbase to see if we can draw meaninfgul insights for a venture capital firm looking to invest in the crypto/blockchain space.
<br></br>
## Goal:
The goal of this project will be threefold:
1. Use EDA to identify meaningful insights from the data
2. Identify company variables most correlated with funding amounts.
3. Train and test the efficacy of a model for predicting funding amounts.
<br></br>
## Data Description:
We will use data taken from [Crunchbase.com](https://www.crunchbase.com/) to conduct this analysis. This includes a dataset where [each row is a funding round](https://www.crunchbase.com/discover/funding_rounds/77238993ceeb2b8e0e84e9ea364a0342), and another where [each row is a company](https://www.crunchbase.com/discover/organization.companies/d5287eff9c642c766d63632c9da4ee22)
<br></br>
## Tools:
- **Pandas** and **NumPy** for Data Ingestion, EDA
- **Seaborn** and **Matplotlib** for Visualization
- **Scikit-learn** for regession analysis and model testing.
<br></br>
## MVP Goal:
Produce an exploratory data analysis of the available data and a baseline model with feature coefficients for future iterations.
