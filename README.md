# Airbnb


## Introduction:
Airbnb is a home-sharing platform that allows home-owners and renters ('hosts') to put their properties ('listings') online, so that guests can pay to stay in them. Hosts are expected to set their own prices for their listings. Although Airbnb and other sites provide some general guidance, there are currently no free services which help hosts price their properties. Paid third party pricing software is available, but generally you are required to put in your own expected average price ('base price'), and the algorithm will vary the daily price around that base price on each day depending on day of the week, seasonality, how far away the date is, and other factors.

Airbnb pricing is important to get right, particularly in big cities like Capetown where there is lots of competition and even small differences in prices can make the difference between optimum occupancy and high earnings, or being priced out of the market. It is also a difficult thing to do correctly, in order to balance the price with occupancy (which varies inversely with price) in order to maximise revenue.

## In this project, I attempt to reach the following tangible goals:  
* Prediction of pricing of Airbnb Listings 
* Regression Models: OLS, XGboost 

## Data:
Data was pull from insideairbnb.com. 

## Conclusions

After experimenting with various machine learning models, the best model was an XGBoost model, which was able to explain 75.04% of the variation in price. The remaining 24.96% is probably made up of features that were not present in the data. It is likely that a significant proportion of this unexplained variance is due to variations in the listing photos. The photos of properties on Airbnb are very important in encouraging guests to book, and so can also be expected to have a significant impact on price - better photos (primarily better quality properties and furnishings, but also better quality photography) equal higher prices.

#### Future Work

   * comparsion to other cities
   * Crime data attached to locations
   * Computer vision to analyze how nice the interiors are
