# NYC AirBnB Price Optimization #
### By: Nate DiRenzo

## Statement of Need:

Optimizing the pricing of AirBnB listings makes sense for all parties involved. For hosts, having a competitive price point helps to maximize profit, without missing any opportunities. For guests, it makes sure they have options, and aren't overpaying for their stay. For AirBnB, it increases user engagement on both sides of transaction, and helps remove the barriers to entry for potential hosts by giving them one less thing to worry about.
<br></br>
## Goal:
The goal of this project is to identify the key features within the dataset that have some predictive power on price. Once we have identified and visualized those relationships, a further goal will be to train and evaluate a linear regression model that can predict a givien listing's price accurately.

## Success Metrics:
The primary goal of this project is to deliver meaningful business impact to our client, AirBnB. In that sense, the deliverable is a cost optimization model that, when put into production, increases both number of listings and number of bookings, as well as reudcing the number of inactive listings, and listings with availability in the next 30 days. This would indicate that our model is removing barriers to entry for potential hosts, optimizing the market for existing listings, and providing a better experience to renters via more options at better price points.
<br></br>
## Data Description:
We will use data taken from [InsideAirBnB.com](http://insideairbnb.com/get-the-data.html) to conduct this analysis. The dataset includes pertinent features for our purposes, such as borough, neighborhood, number of guests accomodated, bedrooms, bathrooms, and many more. A detailed dictionary of the dataset's features can be found [here](https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=982310896).
<br></br>
## Tools:
- **Pandas**, **NumPy**, and **Google Sheets** for Data Ingestion, EDA
- **Seaborn**, **Matplotlib**, and **Tableau Public** for Visualization
- **Scikit-learn** and **XGBoost** for regession analysis and model testing.

<br></br>
## MVP Goal:
Produce an initial analysis of the dataset identifying and visualizing a set of core features and their relationships' with our target variable (listing price). 
