# E-Commerce-Sale-Prediction
Capstone project Submitted towards the partial fulfillment of the criteria for award of Post Graduate In Data Analytics and Machine Learning by Imarticus


## About Dataset
### Aim
    Can we predict if a visitor, in a session, will add item(s) to the cart?

    The E-Commerce Store sells branded merchandise. Using Data Analytics and Machine Learning Models, let’s try and build a model that predicts whether each session will result in the visitor performing an action to add an item to the cart.

### Data Description
    * fullVisitorId: - The unique visitor ID.
    * deviceCategory:- The type of device (Mobile, Tablet, Desktop).
    * isMobile: - If the user is on a mobile device, this value is true, otherwise false.
    * operatingSystem: - The operating system of the device (e.g., "Macintosh" or "Windows").
    * browser: - The browser used (e.g., "Chrome" or "Firefox").
    * country: - The country from which sessions originated, based on IP address.
    * city: - Users' city, derived from their IP addresses or Geographical IDs
    * trafficSource: - The source of the traffic source. Could be the name of the search engine, the referring hostname, or 		a value of the utm_source URL parameter.
    * trafficMedium: - The medium of the traffic source. Could be "organic", "cpc", "referral", or the value of the 			utm_medium URL parameter.
    * trafficCampaign: - The campaign value. Usually set by the utm_campaign URL parameter.
    * isFirstVisit: 0 if this is the first visit made by the visitor, otherwise 1.
    * totalVisits: - The total number of visits by the visitor across sessions.
    * totalHits: - The total number of interactions across sessions.
    * totalPageviews: - The total number of page views across sessions.
    * productPagesViewed: - The number of product pages viewed in the session.
    * addedToCart: - If the visitor added an item to the cart or made further downstream actions (checkout, transaction), 		otherwise 0 (if the visitor only browsed but never added an item to the cart).

    ** Target variable is addedToCart **
    
## Result:
    XGBoost and Logistic Regression seem to be the best-performing models in terms of accuracy, with Logistic Regression having the highest accuracy score of 0.912422. Therefore, either of these models can be considered for E-Commerce sale prediction.
