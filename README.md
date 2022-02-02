# Predicting Funding Rounds for Web3/Blockchain Startups #
### By: Nate DiRenzo

## Statement of Need:
In recent years, web3 and blockchain startups in the US have received a massive influx of venture capital. In 2021 alone, this number exceeded $33 Billion-- more than all other years combined. Among the firms leading the way are firms such as [Paradigm](https://techcrunch.com/2021/11/15/crypto-vc-firm-paradigm-debuts-monster-2-5-billion-fund/) and [Andreessen Horowitz](https://www.coindesk.com/business/2022/01/20/andreessen-horowitz-looks-to-raise-45b-for-new-crypto-funds-report/), both of which have committed over $2 billion to the space in 2021 with more to come in 2022. But what is web3 and blockchain? In some ways it's a [rebranding](https://www.vox.com/recode/22907072/web3-crypto-nft-bitcoin-metaverse#:~:text=Let's%20start%20here%3A%20At%20its,human%20intervention%20or%20centralized%20oversight.) of the more ominous-sounding 'crypto'. In others, it's a more encompassing definition that better captures the opportunity these technologies present for a better version of the internet. Whatever the case may be, it's a space getting a lot of attention from consumers and investers alike. 

Despite this surge in interest for all things blockchain and web3, the space is young, and not well understood. [Some](https://www.nytimes.com/2021/12/20/technology/silicon-valley-cryptocurrency-start-ups.html) see it as the next frontier in innovation, while others think of it merely as a [bubble and a scam](https://www.cnbc.com/2021/12/03/crypto-investors-see-an-nft-bubble-but-tout-power-of-underlying-tech.html). Here, we will evaluate a dataset taken from Crunchbase to see if we can draw meaninfgul insights for a venture capital firm who already has investments in the space, or is looking to invest in the web3/blockchain space.
<br></br>
## Goal:
The goal of this project will be to produce insights that will help a venture capital fund evaluate potential investments in organizations in the web3 space. Specifically, we will seek to identify and understand the relationship between features present in the dataset and the target variable: amount of funding a company has recieved. As a further goal, we will train and evaluate the efficacy of a regression model for predicting total funding amounts.
<br></br>
## Data Description:
We will use data taken from [Crunchbase.com](https://www.crunchbase.com/) to conduct this analysis. This includes a dataset where [each row is a funding round](https://www.crunchbase.com/discover/funding_rounds/77238993ceeb2b8e0e84e9ea364a0342), and another where [each row is a company](https://www.crunchbase.com/discover/organization.companies/d5287eff9c642c766d63632c9da4ee22)
<br></br>
## Tools:
- **Pandas**, **NumPy**, and **Google Sheets** for Data Ingestion, EDA
- **Seaborn**, **Matplotlib**, and **Tableau Public** for Visualization
- **Scikit-learn** for regession analysis and model testing.

<br></br>
## MVP Goal:
Produce an exploratory data analysis of the available data and a baseline model with feature coefficients for future iterations.
