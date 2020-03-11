# Airbnb


## Introduction:
Airbnb made a historic rise in the past decade by allowing everyday homeowners to rent out their homes on their platform. This revolutionized the way people traveled and has become to the go to for many travelers. As we all know for many renters price plays a big factor in the decision making process. So for the host its important that they get the price correct so they can remain competitive with other renters in their area. As of now Airbnb provides with their own recommender system on how they should price their listing. But, with no information on how this is created host have very little knowledge on why they should price their home at a certain price point. So by creating a price predictor, I'm hoping to provide host with a clearer view on what goes into the price. 

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
