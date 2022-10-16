### Wine Reviews and Impact on Wine Pricing
#### WineEnthusiast is a very popular magazine for wine consumers, ranging from the curious consumer to the master sommelier. This well known site also functions as a shopping site. There is a lot of educational articles about wine so this is also an educational site. Additonally, people can post their reviews on a wide variety of wines, making this an interactive blogging platform. 
************************************************************************************************
#### Wine is important because it has a lot of significance in many different cultures around the world. The most obvious area of the world is of course Europe, although it is also heavily emphasized everywhere else in the world. Many people enjoy and consume wine, making this a very relatable commodity. More importantly this is a highly desirable commodity, and ideally people would like to purchase good quality wine in relation to their purchase price. In the interest of the wine consumer, I would like to analyze wine reviews to predict its purchase price.
************************************************************************************************
#### Questions to consider:
#### Do better reviews lead to higher price? What kind of relationship do they have?
#### Which countries of origin are most talked about?
#### Which are the most talked about provinces per country of origin?
************************************************************************************************
#### This data was downloaded from Kaggle.com. The data was scraped from WineEnthusiast during the week of November 22nd, 2017 by zachthoutt. It is 53 MB. 
#### https://www.kaggle.com/datasets/zynicide/wine-reviews?select=winemag-data_first150k.csv
************************************************************************************************
#### After cleaning, the data shape is 129,971 rows, and 12 columns. 
#### The data is mostly categorical, but this will be handled later using one hot encoding. 
#### Relevant units of analysis include country, province, regions, wineries etc.
#### The two numeric columns are price and points. The price is the purchase price and points refers to the score or rating of the wine, out of 100. 
************************************************************************************************
#### I will use linear regression models to predict the price. I can evaluate the models using the correlation coefficient by producing a line of best fit.
#### First, I will perform simple regression with the independent variable of review points. 
#### Then, I will perform multivariate regression via encoding the categorical variables. One hot encoding will be used to convert the categorical variables into a usable numeric form. 
************************************************************************************************
#### The goal is to use reviews to predict price.
#### Another goal is to discover and visualize trends. 
#### I would like people to have a good idea about how good of a quality wine they are getting in relation to what they spend, and therefore help them gauge what is worth purchasing. Also, I would like people to know any patterns that exist in WineEnthusiast reviews, because this is a widely referenced and trusted site. 
